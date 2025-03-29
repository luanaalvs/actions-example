# GitHub Actions

GitHub Actions é uma ferramenta de automação integrada ao GitHub. Por meio de um conjunto de instruções, ele cria fluxos de trabalho acionados por eventos, como `push` e `pull_request`, para automatizar tarefas no repositório, incluindo deploys, testes e diversas outras ações.

## Como funciona?

Um **workflow** é acionado quando um **evento** ocorre dentro do repositório. Esse fluxo de trabalho contém uma série de etapas **(jobs)** que podem ser executados de forma sequencial ou paralela. Cada etapa é executada dentro de um **runner**.

## Componentes do GitHub Actions

- **Workflows**: são um conjunto de tarefas automatizadas que respondem a um ou mais **eventos** acionados dentro de um repositório.
- **Events**: os eventos são gatilhos que acionam a execução de um workflow.
- **Jobs**: são uma série de etapas e cada etapa pode executar um script ou rodar uma ação dentro do workflow.
- **Actions**: as actions são blocos de códigos reutilizáveis que executam tarefas específicas dentro do workflow.
- **Runners**: um runner é um servidor onde os jobs são executados.
