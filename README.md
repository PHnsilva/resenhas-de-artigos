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
   ├─ criteria-for-modularization/
   │  ├─ criteria_for_modularization.md
   │  └─ criteria_for_modularization.pdf
   ├─ design-by-contract/
   │  ├─ resenha_design_by_contract.md
   │  └─ resenha_design_by_contract.pdf
   ├─ facade/
   │  ├─ resenha_facade.md
   │  └─ resenha_facade.pdf
   ├─ hexagonal-architecture/
   │  ├─ resenha_hexagonal_architecture.md
   │  └─ resenha_hexagonal_architecture.pdf
   ├─ microservicos-martin-fowler/
   │  ├─ resenha_microservicos.md
   │  └─ resenha_microservicos.pdf
   ├─ No-Silver-Bullet-Essence-and-Accidents-of-Software-Engineering/
   │  ├─ resenha_no_silver_bullet.md
   │  └─ resenha_no_silver_bullet.pdf
   ├─ object-constraint-language-definitive-guide/
   │  ├─ resenha_object_constraint_language.md
   │  └─ resenha_object_constraint_language.pdf
   ├─ resenha_mcp_landscape_security_threats_future_research/
   │  ├─ resenha_mcp_landscape_security_threats_future_research.md
   │  └─ resenha_mcp_landscape_security_threats_future_research.pdf
   └─ software-architecture-a-roadmap/
      ├─ resenha_software_architecture_a_roadmap.md
      └─ resenha_software_architecture_a_roadmap.pdf
```

## Padrão das resenhas

As resenhas seguem o modelo padronizado do projeto, inspirado no formato adotado nos PDFs do repositório.

Cada resenha deve conter:

1. **Título principal** no formato `Resenha: {Título do artigo}`
2. **Subtítulo** com síntese do tema ou do enfoque do texto
3. **Referência bibliográfica completa**
4. **Introdução**
5. **Síntese das ideias principais**, organizada em subtópicos numerados quando necessário
6. **Aplicação prática imaginada**
7. **Conclusão**

Esse padrão ajuda a manter consistência visual e textual entre os arquivos em `.md`, `.pdf` e `.docx`, além de facilitar a leitura e a organização do repositório.

## Como adicionar uma nova resenha

1. Criar uma nova pasta dentro de `resenhas/`.
2. Usar `templates/TEMPLATE_RESENHAS.md` como base.
3. Salvar a versão em Markdown.
4. Gerar a versão final em PDF.
5. Atualizar este README com a nova entrada, quando necessário.

## Observações

- O repositório prioriza organização, legibilidade e padronização.
- A estrutura foi pensada para facilitar versionamento e consulta futura.
- Sempre que possível, mantenha os nomes de arquivos curtos, consistentes e sem ambiguidade.
