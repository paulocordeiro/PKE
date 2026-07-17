# PKE — Project Knowledge Engine

> Uma especificação aberta para representar, planejar e entregar conhecimento de projetos de software a agentes de IA.

[English](README.md)

## Estado atual

O PKE está em sua fase fundacional e de pesquisa. O projeto segue uma abordagem de **especificação primeiro**: os conceitos e contratos de interoperabilidade são definidos antes de uma implementação de referência.

## Motivação

O conhecimento de um projeto de software está distribuído entre código-fonte, testes, registros de arquitetura, issues, pull requests, documentação, esquemas, logs e conversas. Enviar mais desses artefatos a um agente de IA não necessariamente melhora suas decisões; frequentemente aumenta custo, latência, contradições e perda de foco.

O PKE pretende definir como sistemas podem:

1. representar o conhecimento do projeto independentemente de sua origem;
2. determinar o conhecimento necessário para uma tarefa;
3. recuperar o menor conjunto suficiente de evidências;
4. montar contexto para qualquer agente de IA compatível.

## Posição central

**Conhecimento é um ativo. Contexto é um mecanismo de entrega.**

O PKE é projetado para o desenvolvimento assistido por IA, mantendo-se independente de fornecedores de modelos, frameworks de agentes, IDEs, linguagens de programação e tecnologias de armazenamento.

## Princípios de trabalho

O projeto é orientado pelos [Princípios Fundadores](FOUNDING_PRINCIPLES.pt-BR.md), incluindo o **Knowledge Budget**: todo novo conceito e artefato possui um custo permanente de manutenção e deve eliminar mais complexidade do que introduz.

## Idiomas da documentação

A documentação normativa e de nível de projeto é mantida em:

- inglês, usado como arquivo padrão;
- português do Brasil, identificado pelo sufixo `.pt-BR.md`.

As duas versões devem preservar o mesmo significado. Divergências devem ser tratadas como defeitos de documentação.

## Escopo atual

O trabalho inicial está intencionalmente limitado a:

- definir o problema e a terminologia;
- estabelecer o modelo de conhecimento;
- especificar planejamento de conhecimento e montagem de contexto;
- definir um protocolo interoperável;
- descrever uma arquitetura de referência.

Decisões de implementação permanecem abertas até que a especificação forneça evidências suficientes para tomá-las.

## Licença

A licença será escolhida antes da aceitação de contribuições externas ou da publicação de versões normativas da especificação.
