# Oficina de Processos de Software

**Sistema Web Educacional para compreensão e comparação de processos de desenvolvimento de software**

> **PROPRIEDADE INTELECTUAL — TODOS OS DIREITOS RESERVADOS**  
> Este projeto **não está sob licença de código aberto**. Sua consulta, cópia ou disponibilidade em uma plataforma de hospedagem **não constituem autorização para republicação, redistribuição, adaptação ou exploração comercial**. O artigo acadêmico tem regras específicas de **publicação restrita e reconhecimento obrigatório de autoria**, descritas abaixo e nos termos anexos.

## Sobre o projeto

A *Oficina de Processos de Software* é um protótipo educacional interativo voltado a estudantes da área de tecnologia. Seu objetivo é demonstrar como as características de um projeto influenciam a escolha e a aplicação de um processo de desenvolvimento de software.

O trabalho está estruturado em três etapas acadêmicas integradas:

| Etapa | Foco | Materiais disponíveis |
| --- | --- | --- |
| **TP1** | Análise de processos, construção de cenários e quadros digitais | Caderno de cenários, análises e histórias ilustradas |
| **TP2** | Projeto e desenvolvimento do protótipo web | Aplicação HTML, requisitos, arquitetura e documentação TRACE |
| **TP3** | Avaliação de usabilidade e compreensão do conteúdo | Protocolo, tarefas, formulários, rubricas e instrumentos de coleta |

**Status acadêmico:** o protótipo e a documentação estão preparados. A avaliação empírica do TP3 **ainda precisa ser aplicada a participantes reais**; os formulários e relatórios disponibilizados são instrumentos/modelos, não resultados de uma pesquisa concluída.

## Conteúdo educacional

O sistema apresenta três abordagens de processo:

- **Cascata:** organização predominantemente sequencial, planejamento, requisitos, projeto, implementação, testes e manutenção.
- **Processo Unificado / RUP:** desenvolvimento iterativo e incremental, com concepção, elaboração, construção e transição.
- **Scrum com práticas de XP:** organização ágil do trabalho em Sprints, feedback contínuo e práticas técnicas de qualidade.

Cada abordagem é explorada em **três domínios fictícios — Saúde, Agronegócio e Varejo —**, totalizando **nove cenários**. As narrativas incluem situações-problema, participantes, atividades, decisões, entradas, processamento, saídas, artefatos, riscos e análise crítica da adequação do processo.

Além das descrições, o material contém **39 etapas didáticas ilustradas**, organizadas em sequências narrativas, e um acervo de **43 imagens** relacionado aos cenários.

## Como executar

O protótipo foi desenvolvido como um arquivo HTML autocontido, com recursos incorporados, para consulta local.

1. Acesse a pasta [`software/`](software/).
2. Abra o arquivo [`oficina_processos.html`](software/oficina_processos.html) em um navegador atualizado.
3. Escolha um processo de software, selecione o domínio e explore as etapas, quadrinhos, características e análises.

**Não é necessário instalar dependências, executar um servidor ou criar banco de dados** para consultar esta versão do protótipo. Para a apresentação acadêmica, recomenda-se testar previamente a abertura local no navegador utilizado.

## Organização do material

```text
.
├── README.md                               # Apresentação para o GitHub
├── LICENCA_PROPRIEDADE_INTELECTUAL.md     # Condições gerais de uso
├── LICENCA_PROPRIEDADE_INTELECTUAL.pdf
├── LICENCA_ARTIGO_PUBLICACAO_RESTRITA.md  # Restrições específicas do artigo
├── LICENCA_ARTIGO_PUBLICACAO_RESTRITA.pdf
├── TERMO_ARTIGO_PROIBICAO_PUBLICACAO_E_CREDITO_AUTORAL.pdf
├── software/
│   └── oficina_processos.html             # Protótipo web
├── documentos/                            # TP1, TP2 e TP3 em PDF/DOCX
├── artigo/
│   ├── artigo_20_paginas.pdf              # Artigo acadêmico (acesso restrito)
│   ├── artigo_20_paginas.tex              # Fonte LaTeX (acesso restrito)
│   └── quadros/                           # Figuras do artigo
├── instrumentos/                          # Instrumentos e análise do TP3
└── anexos/                                # Imagens, evidências e enunciado
```

> **Atenção:** a estrutura acima descreve a **entrega acadêmica privada**. Em um repositório **público**, não inclua os arquivos identificados como de acesso restrito sem a autorização necessária; consulte a seção “Publicação no GitHub”.

## Artigo acadêmico — 20 páginas

O trabalho é acompanhado do artigo **“Oficina de Processos de Software”**, com **20 páginas**, contemplando a fundamentação sobre os processos, nove estudos de caso, análise comparativa, especificação do sistema, abordagem TRACE, verificação técnica e planejamento de avaliação com SUS, UEQ e instrumentos de compreensão do conteúdo.

- **PDF:** [`artigo/artigo_20_paginas.pdf`](artigo/artigo_20_paginas.pdf) — **somente em repositório privado autorizado**.
- **Fonte editável:** [`artigo/artigo_20_paginas.tex`](artigo/artigo_20_paginas.tex) — **somente em repositório privado autorizado**.
- **Formatação:** segue organização acadêmica semelhante à utilizada pela SBC; a conformidade com o **template oficial específico** precisa ser confirmada antes da submissão.
- **Resultados de pesquisa:** o artigo **não afirma resultados de avaliação com participantes**, pois essa etapa ainda não foi executada.

### Proibição de publicação sem autorização

**A disponibilização do artigo para correção, avaliação ou consulta acadêmica interna não autoriza sua publicação.** É proibida, salvo hipóteses legalmente permitidas, qualquer publicação ou disponibilização pública do artigo, integral ou parcial, inclusive em versão traduzida, resumida ou adaptada, **sem autorização prévia, expressa e por escrito dos titulares dos direitos envolvidos**.

A restrição alcança, conforme os direitos efetivamente detidos, **revistas, congressos, anais, sites, blogs, redes sociais, plataformas de documentos, repositórios institucionais públicos, GitHub, GitHub Pages e outros meios físicos ou digitais**. O acesso ao arquivo, o recebimento de uma cópia ou a indicação da fonte não concedem, por si só, licença de publicação.

### Crédito obrigatório à autoria

A autorização para um uso público, caso venha a ser concedida, **não elimina a obrigação de reconhecer corretamente a autoria**. Em qualquer uso autorizado, devem ser observadas as condições da autorização e os direitos morais aplicáveis, incluindo identificação clara da autora junto ao título e nos metadados disponíveis, sem substituição, supressão ou atribuição indevida de autoria.

**Citar a autora não equivale a ter permissão para publicar. Ter permissão para publicar não autoriza omitir o crédito da autora.**

**Identificação da autora:** `Letícia Cardoso Mendonça Mustafá Awawdeh`  
**Titularidade patrimonial:** `Letícia Cardoso Mendonça Mustafá Awawdeh `

Os campos acima e as informações correspondentes no artigo e nos termos devem ser preenchidos e confirmados antes do depósito acadêmico. Os direitos de possíveis coautores e terceiros não são afastados por esta declaração.

### Consequências de uso não autorizado

A publicação indevida, a remoção do crédito de autoria ou a falsa atribuição podem dar origem, **conforme as circunstâncias e a legislação aplicável**, a pedidos de retirada de conteúdo, correção de autoria, medidas extrajudiciais ou judiciais e eventual reparação por danos. Nenhum aviso contratual afasta exceções legais nem determina, por si só, a procedência de uma demanda.

**Documentos que regem esta matéria:**

- [`LICENCA_ARTIGO_PUBLICACAO_RESTRITA.md`](LICENCA_ARTIGO_PUBLICACAO_RESTRITA.md) e sua [versão PDF](LICENCA_ARTIGO_PUBLICACAO_RESTRITA.pdf);
- [`TERMO_ARTIGO_PROIBICAO_PUBLICACAO_E_CREDITO_AUTORAL.pdf`](TERMO_ARTIGO_PROIBICAO_PUBLICACAO_E_CREDITO_AUTORAL.pdf);
- [`LICENCA_PROPRIEDADE_INTELECTUAL.md`](LICENCA_PROPRIEDADE_INTELECTUAL.md) e sua [versão PDF](LICENCA_PROPRIEDADE_INTELECTUAL.pdf).

Referência jurídica geral: **Lei brasileira nº 9.610/1998**, especialmente seus dispositivos sobre direitos morais, autorização de uso e medidas de tutela, sempre observadas as exceções legais e os direitos de terceiros.

## Licença do projeto

**© 2026 — Todos os direitos reservados sobre as partes autorais do projeto aos respectivos titulares, a confirmar.**

Este repositório **não é automaticamente livre para uso, cópia, modificação ou redistribuição** por estar hospedado no GitHub. **Não se aplicam as licenças MIT, Apache, GPL ou Creative Commons** aos componentes autorais por mera presunção. A documentação prevê usos necessários à apresentação e avaliação acadêmica, nos seus limites, sem transferir a titularidade.

A licença do projeto não reivindica direitos sobre textos de terceiros, referências bibliográficas, o enunciado da disciplina, softwares ou instrumentos de terceiros, incluindo SUS e UEQ. Esses itens continuam sujeitos às suas próprias condições jurídicas.

## Publicação no GitHub: recomendações de acesso

**Para preservar a restrição de publicação do artigo, utilize um repositório privado para o pacote acadêmico completo.**

- **Repositório privado:** armazenar o HTML, a documentação e o artigo apenas com acesso concedido às pessoas autorizadas, observando as regras da instituição e dos titulares.
- **Repositório público:** publicar este README **não autoriza** disponibilizar o artigo PDF, a fonte LaTeX, o termo com dados pessoais, os quadros ou outros materiais protegidos sem verificar a autorização pertinente. Exclua os arquivos restritos do conteúdo público; não basta escrever “todos os direitos reservados” depois de divulgá-los.
- **Histórico do Git:** se o artigo já tiver sido enviado a um repositório público, apagar o arquivo em um novo commit pode não removê-lo do histórico, de forks ou de cópias existentes. É necessário tratar a exposição e suas consequências separadamente.
- **GitHub Pages e releases:** são meios de distribuição pública; não use esses canais para hospedar o artigo sem a autorização exigida.

A hospedagem em um repositório privado também deve respeitar contratos, direitos de terceiros e políticas institucionais aplicáveis.

## Como solicitar autorização ou citar o projeto

Qualquer solicitação de publicação, reprodução além da permissão acadêmica, adaptação, distribuição ou uso comercial deve ser encaminhada **previamente à titular dos direitos**, para análise e eventual autorização **expressa e documentada**, com definição do material, finalidade, meio de divulgação, duração e forma de atribuição.

**Contato para autorizações:** `[INFORMAR E-MAIL INSTITUCIONAL OU CONTATO AUTORIZADO]`  
**Autoria e filiação:** `[INFORMAR NOME COMPLETO, CURSO E INSTITUIÇÃO]`

A citação acadêmica feita dentro das limitações legais não deve ser confundida com autorização para hospedar, publicar ou reproduzir integralmente o artigo.

## Limitações e próximos passos acadêmicos

- Confirmar dados de autoria, titularidade e eventuais coautores nos documentos e nos metadados.
- Confirmar os requisitos de formatação da SBC estabelecidos pela disciplina.
- Aplicar o protocolo de avaliação do TP3 a participantes reais e completar o relatório com dados genuínos e procedimentos institucionais adequados.
- Validar permissões relativas a imagens, instrumentos e materiais de terceiros antes de qualquer publicação pública.

---

**Uso acadêmico restrito. Publicação do artigo somente mediante autorização prévia, expressa e escrita dos titulares pertinentes, com reconhecimento adequado da autoria.**
