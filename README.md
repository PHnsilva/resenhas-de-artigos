# Resenhas de Artigos

Repositório dedicado ao armazenamento e à organização de resenhas acadêmicas e técnicas sobre arquitetura de software, engenharia de software e temas relacionados.

## Estado do acervo

As dez resenhas atuais estão finalizadas. O repositório permanece aberto a novas leituras e resenhas. Revisões e acréscimos devem preservar a autoria e identificar as fontes consultadas.

## Objetivo

Este repositório reúne resenhas de artigos, capítulos e textos técnicos da área de computação.
O objetivo é manter um acervo consistente e fácil de navegar, com uma pasta por texto e os arquivos finais organizados por formato.

## Organização

- Cada texto resenhado possui uma pasta própria dentro de `resenhas/`.
- O nome da pasta deve identificar o texto resenhado de forma clara.
- Os arquivos da resenha seguem, de preferência, o padrão `resenha_<slug>.<ext>`.
- O template-base para novas resenhas fica em `templates/TEMPLATE_RESENHAS.md`.

## Estrutura

```txt
.
├─ README.md
├─ REFERENCIAS.md
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
      ├─ resenha_software_architecture_roadmap.md
      └─ resenha_software_architecture_roadmap.pdf
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

Esse padrão ajuda a manter consistência visual e textual entre os arquivos em `.md` e `.pdf`, além de facilitar a leitura e a organização do repositório.

## Consulta do acervo

Consulte o [catálogo de referências](REFERENCIAS.md) para localizar as fontes originais, conceitos e cuidados de aplicação. Abra [resenhas/](resenhas/) para acessar os pares Markdown/PDF e use o [template](templates/TEMPLATE_RESENHAS.md) como referência. O repositório contém documentos, sem aplicação, dependências ou comando de build automatizado para os PDFs.

## Como adicionar uma nova resenha

1. Criar uma nova pasta dentro de `resenhas/`.
2. Usar `templates/TEMPLATE_RESENHAS.md` como base e conferir autoria, edição, data, DOI ou URL da fonte original.
3. Salvar a versão em Markdown.
4. Gerar a versão final em PDF.
5. Conferir nomes, links e legibilidade do PDF.
6. Atualizar este README e `REFERENCIAS.md` com a nova entrada e abrir um pull request.

## Observações

- O repositório prioriza organização, legibilidade e padronização.
- A estrutura foi pensada para facilitar versionamento e consulta futura.
- Sempre que possível, mantenha os nomes de arquivos curtos, consistentes e sem ambiguidade.

## Autoria e licença

As referências bibliográficas dos textos resenhados estão em cada documento. Não há arquivo de licença no repositório. Os artigos citados mantêm seus próprios direitos e condições de uso.
