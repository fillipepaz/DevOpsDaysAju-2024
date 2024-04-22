# Informações sobre projeto apresentado no DevOps Days Aracaju 2024

## Estrutura da Prova de Conceito

![Estrutura Apresentada](https://github.com/fillipepaz/DevOpsDaysAju-2024/blob/main/arch/arch.png "Estrutura Apresentada")

## Versionamento da Infraestrutura
Repositório onde serão abertos os pull requests com as solicitações de provisionamento de infraestrutura.
[Link para o repositório do versionamento](https://github.com/fillipepaz/infrastructure-versioning)

## Backstage
Framework para construção do Internal Developer Portal.
[Link para o repositório do Backstage](https://github.com/fillipepaz/backstage-project)

## Módulo para provisionamento da CDN
Repositório contendo o módulo Terraform que abstrai o conjunto de recursos necessários para a entrega da estrutura para o site estático.
[Link para o repositório do módulo](https://github.com/fillipepaz/aws-cloudfront-module)

## Atlantis
Foi utilizada a versão 4.20.0 do Helm Chart do Atlantis. É possível encontrar em: [https://github.com/runatlantis/helm-charts/releases/tag/atlantis-4.20.0](https://github.com/runatlantis/helm-charts/releases/tag/atlantis-4.20.0)
Será necessário configurar um ingress com IP público para receber os Webhooks do serviço de Git escolhido.
A configuração do webhook pode ser encontrada no link: [https://www.runatlantis.io/docs/configuring-webhooks.html#github-github-enterprise](https://www.runatlantis.io/docs/configuring-webhooks.html)
