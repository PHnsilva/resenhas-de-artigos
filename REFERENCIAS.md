# Referências das resenhas

Referências conferidas em 10/10/2026 nas páginas dos autores, editoras e registros DOI. As resenhas são sínteses e interpretações; aplicações imaginadas são exemplos, sem comprovar implementações entregues. Os princípios devem ser aplicados conforme o problema e as instruções do projeto.

O acervo atual tem dez resenhas finalizadas e permanece aberto a novos textos. A numeração das fontes acompanha cada resenha; as fontes originais continuam sujeitas às suas próprias condições de uso.

## 1. Big Ball of Mud

FOOTE, Brian; YODER, Joseph. **Big Ball of Mud**. PLoP/EuroPLoP 1997, Technical Report WUCS-97-34. Versão de 26 jun. 1999. Publicado também em _Pattern Languages of Program Design 4_, cap. 29, 2000.

[Resenha](resenhas/1997-big-ball-of-mud/resenha_big_ball_of_mud.md) | [PDF](resenhas/1997-big-ball-of-mud/resenha_big_ball_of_mud.pdf)

Pressões de prazo e mudanças favorecem erosão arquitetural. Evolução incremental precisa de consolidação, separação por ritmo de mudança e isolamento de legado.

**Aplicação:** Diagnosticar acoplamento e organizar refatorações pequenas que mantenham o sistema funcionando.

**Cuidado:** Não tratar o texto como incentivo a código desorganizado ou justificativa automática para reescrita completa.

**Fontes:** [Fonte 1](https://www.laputan.org/mud/)

## 2. On the Criteria To Be Used in Decomposing Systems into Modules

PARNAS, David L. **On the Criteria To Be Used in Decomposing Systems into Modules**. _Communications of the ACM_, v. 15, n. 12, p. 1053-1058, dez. 1972. DOI: [10.1145/361598.361623](https://doi.org/10.1145/361598.361623).

[Resenha](resenhas/criteria-for-modularization/criteria_for_modularization.md) | [PDF](resenhas/criteria-for-modularization/criteria_for_modularization.pdf)

Definir módulos para esconder decisões de projeto que podem variar, com interfaces pequenas; a sequência do processamento não basta como critério de decomposição.

**Aplicação:** Revisar fronteiras de módulos, contratos e impacto de mudanças em armazenamento, políticas e integrações.

**Cuidado:** Information hiding não exige multiplicar camadas ou criar abstrações sem uma decisão concreta a isolar.

**Fontes:** [Fonte 1](https://doi.org/10.1145/361598.361623)

## 3. Design by Contract

MEYER, Bertrand. **Design by Contract**. In: MANDRIOLI, Dino; MEYER, Bertrand (eds.). _Advances in Object-Oriented Software Engineering_. Prentice Hall, 1991. cap. 1, p. 1-50.

[Resenha](resenhas/design-by-contract/resenha_design_by_contract.md) | [PDF](resenhas/design-by-contract/resenha_design_by_contract.pdf)

Precondições, pós-condições e invariantes tornam responsabilidades verificáveis. Redefinições não devem fortalecer precondições nem enfraquecer pós-condições.

**Aplicação:** Explicitar invariantes de domínio e contratos de operações e orientar testes de comportamento e falhas.

**Cuidado:** Contratos internos não substituem validação de dados externos, autenticação ou autorização. O texto consultado é o capítulo de 1991, distinto do artigo IEEE de 1992.

**Fontes:** [Fonte 1](https://se.inf.ethz.ch/~meyer/publications/old/dbc_chapter.pdf) | [Fonte 2](https://se.inf.ethz.ch/~meyer/publications/)

## 4. Facade

REFACTORING.GURU. **Facade**. In: _Design Patterns_, Structural Patterns. [S. l.], [s. d.]. Acesso em: 10 out. 2026.

[Resenha](resenhas/facade/resenha_facade.md) | [PDF](resenhas/facade/resenha_facade.pdf)

Uma fachada oferece acesso simplificado a um subsistema e reduz o conhecimento que o cliente precisa ter dos detalhes internos.

**Aplicação:** Concentrar composição técnica de bibliotecas e fluxos repetidos atrás de uma interface pequena.

**Cuidado:** Evitar uma fachada que concentre responsabilidades demais; diferenciar simplificação de acesso, adaptação de contrato e mediação. O copyright 2014-2026 não é uma data de publicação.

**Fontes:** [Fonte 1](https://refactoring.guru/design-patterns/facade)

## 5. The Hexagonal (Ports & Adapters) Architecture

COCKBURN, Alistair. **The Hexagonal (Ports & Adapters) Architecture**. HaT Technical Report 2005.02, versão 0.9, 4 set. 2005.

[Resenha](resenhas/hexagonal-architecture/resenha_hexagonal_architecture.md) | [PDF](resenhas/hexagonal-architecture/resenha_hexagonal_architecture.pdf)

Separar a aplicação do mundo externo usando portas por propósito e adaptadores substituíveis; permitir testes do núcleo sem interface ou banco real.

**Aplicação:** Proteger regras de negócio ao trocar interfaces, persistência e provedores externos e facilitar testes isolados.

**Cuidado:** Seis lados não significam seis camadas ou seis portas obrigatórias. Adaptadores de teste não demonstram integração com dispositivos e serviços reais.

**Fontes:** [Fonte 1](https://alistair.cockburn.us/hexagonal-architecture)

## 6. Microservices

LEWIS, James; FOWLER, Martin. **Microservices**. MartinFowler.com, 25 mar. 2014. Acesso em: 10 out. 2026.

[Resenha](resenhas/microservicos-martin-fowler/resenha_microservicos.md) | [PDF](resenhas/microservicos-martin-fowler/resenha_microservicos.pdf)

Serviços implantáveis independentemente e organizados por capacidades de negócio exigem automação, responsabilidade operacional e desenho para falhas.

**Aplicação:** Avaliar autonomia de equipes, fronteiras de serviço e custos de dados e operação distribuídos.

**Cuidado:** Não adotar microserviços por tendência; justificar a divisão pelo problema e pelos custos de comunicação, consistência e operação.

**Fontes:** [Fonte 1](https://martinfowler.com/articles/microservices.html)

## 7. No Silver Bullet: Essence and Accidents of Software Engineering

BROOKS JR., Frederick P. **No Silver Bullet: Essence and Accidents of Software Engineering**. _Computer_, v. 20, n. 4, p. 10-19, abr. 1987. DOI: [10.1109/MC.1987.1663532](https://doi.org/10.1109/MC.1987.1663532).

[Resenha](resenhas/No-Silver-Bullet-Essence-and-Accidents-of-Software-Engineering/resenha_no_silver_bullet.md) | [PDF](resenhas/No-Silver-Bullet-Essence-and-Accidents-of-Software-Engineering/resenha_no_silver_bullet.pdf)

Distinguir dificuldades essenciais do domínio e da concepção das dificuldades acidentais das ferramentas. Ganhos consistentes dependem de trabalho incremental e entendimento do problema.

**Aplicação:** Avaliar promessas de ferramentas, métodos e automações com evidência e preservar clareza de requisitos e integridade conceitual.

**Cuidado:** A análise histórica não demonstra que toda ferramenta atual tenha impacto pequeno nem sustenta estimativas quantitativas sem medição.

**Fontes:** [Fonte 1](https://doi.org/10.1109/MC.1987.1663532) | [Fonte 2](https://api.crossref.org/works/10.1109/MC.1987.1663532)

## 8. Object Constraint Language (OCL): A Definitive Guide

CABOT, Jordi; GOGOLLA, Martin. **Object Constraint Language (OCL): A Definitive Guide**. In: BERNARDO, Marco; CORTELLESSA, Vittorio; PIERANTONIO, Alfonso (eds.). _Formal Methods for Model-Driven Engineering_. Berlin, Heidelberg: Springer, 2012. LNCS, v. 7320, p. 58-90. DOI: [10.1007/978-3-642-30982-3_3](https://doi.org/10.1007/978-3-642-30982-3_3).

[Resenha](resenhas/object-constraint-language-definitive-guide/resenha_object_constraint_language.md) | [PDF](resenhas/object-constraint-language-definitive-guide/resenha_object_constraint_language.pdf)

Complementar UML com restrições tipadas sem efeitos colaterais, invariantes e contratos; ordem e repetição importam nas coleções, e null e invalid precisam ser distinguidos.

**Aplicação:** Especificar regras críticas de consistência do domínio e manter rastreabilidade entre modelo, validações e testes.

**Cuidado:** Conferir a versão de OCL e o suporte da ferramenta. A especificação não valida automaticamente o código; não reduzir a semântica a três valores quando null e invalid são distintos.

**Fontes:** [Fonte 1](https://link.springer.com/chapter/10.1007/978-3-642-30982-3_3) | [Fonte 2](https://www.db.informatik.uni-bremen.de/publications/Cabot_2012_SFM.pdf) | [Fonte 3](https://www.omg.org/spec/OCL/2.4/PDF)

## 9. Model Context Protocol (MCP): Landscape, Security Threats, and Future Research Directions

HOU, Xinyi; ZHAO, Yanjie; WANG, Shenao; WANG, Haoyu. **Model Context Protocol (MCP): Landscape, Security Threats, and Future Research Directions**. _ACM Transactions on Software Engineering and Methodology_, v. 35, n. 10, p. 1-37, 2026. DOI: [10.1145/3796519](https://doi.org/10.1145/3796519). Publicação online: 16 set. 2026.

[Resenha](resenhas/resenha_mcp_landscape_security_threats_future_research/resenha_mcp_landscape_security_threats_future_research.md) | [PDF](resenhas/resenha_mcp_landscape_security_threats_future_research/resenha_mcp_landscape_security_threats_future_research.pdf)

Analisar integração com ferramentas e fronteiras de confiança ao longo de criação, implantação, operação e manutenção; tratar riscos de metadados, prompt injection, credenciais e encadeamento de ferramentas.

**Aplicação:** Revisar permissões, isolamento, versionamento, auditoria e origem de servidores e ferramentas de agentes.

**Cuidado:** A v3 do preprint tem quatro fases; não confundir com a v1, que tinha três. Este estudo não substitui a especificação atual do MCP nem concede autorização a conteúdo de ferramentas.

**Fontes:** [Fonte 1](https://doi.org/10.1145/3796519) | [Fonte 2](https://arxiv.org/abs/2503.23278v3) | [Fonte 3](https://api.crossref.org/works/10.1145/3796519)

## 10. Software Architecture: a Roadmap

GARLAN, David. **Software Architecture: a Roadmap**. In: FINKELSTEIN, Anthony (ed.). _Proceedings of the Conference on The Future of Software Engineering_. New York: ACM Press, 2000. p. 91-101. DOI: [10.1145/336512.336537](https://doi.org/10.1145/336512.336537).

[Resenha](resenhas/software-architecture-a-roadmap/resenha_software_architecture_roadmap.md) | [PDF](resenhas/software-architecture-a-roadmap/resenha_software_architecture_roadmap.pdf)

Arquitetura liga requisitos, estruturas, atributos de qualidade e evolução; explicitar pressupostos e decisões ajuda a enfrentar incompatibilidades de integração.

**Aplicação:** Documentar componentes, conectores, compromissos de qualidade e decisões arquiteturais com razões e consequências.

**Cuidado:** O panorama é de 2000: usar os princípios, sem apresentar previsões ou estado histórico de ferramentas como descrição atual.

**Fontes:** [Fonte 1](https://www.cs.cmu.edu/~able/publications/roadmap2000/) | [Fonte 2](https://doi.org/10.1145/336512.336537)
