# Resenhas de Artigos

Repositório dedicado ao armazenamento e à organização de resenhas acadêmicas e técnicas sobre arquitetura de software, engenharia de software e temas relacionados.

## Objetivo

Este repositório reúne resenhas produzidas a partir de artigos clássicos e contemporâneos da área de computação.  
A ideia é manter um acervo simples, consistente e fácil de navegar, com uma pasta por artigo e os arquivos finais organizados por formato.

## Organização

- Cada artigo possui uma pasta própria dentro de `resenhas/`.
- O nome da pasta deve identificar o texto resenhado de forma clara.
- Os arquivos da resenha seguem, de preferência, o padrão `resenha_<slug>.<ext>`.
- O template-base para novas resenhas fica em `templates/TEMPLATE_RESENHAS.md`.

## Estrutura

```txt
.
├─ README.md
├─ templates/
│  └─ TEMPLATE_RESENHAS.md
└─ resenhas/
   ├─ 1997-big-ball-of-mud/
   │  ├─ resenha_big_ball_of_mud.md
   │  └─ resenha_big_ball_of_mud.pdf
   ├─ microservicos-martin-fowler/
   │  ├─ resenha_microservicos.md
   │  └─ resenha_microservicos.pdf
   ├─ No-Silver-Bullet-Essence-and-Accidents-of-Software-Engineering/
   │  ├─ resenha_no_silver_bullet.md
   │  └─ resenha_no_silver_bullet.pdf
   └─ criteria-for-modularization/
      ├─ resenha_criteria_for_modularization.md
      └─ resenha_criteria_for_modularization.docx
```

## Padrão das resenhas

As resenhas seguem a estrutura definida no template do projeto:

1. Título do artigo e ano
2. Referência bibliográfica
3. Ideia central
4. Principais pontos
5. Aplicação prática imaginada
6. Conclusão

Esse padrão ajuda a manter consistência entre os textos e facilita a leitura no repositório.

## Como adicionar uma nova resenha

1. Criar uma nova pasta dentro de `resenhas/`.
2. Usar `templates/TEMPLATE_RESENHAS.md` como base.
3. Salvar a versão em Markdown.
4. Gerar a versão final em PDF ou DOCX, conforme a proposta da atividade.
5. Atualizar este README com a nova entrada, quando necessário.

## Observações

- O repositório prioriza organização, legibilidade e padronização.
- A estrutura foi pensada para facilitar versionamento e consulta futura.
- Sempre que possível, mantenha os nomes de arquivos curtos, consistentes e sem ambiguidade.
