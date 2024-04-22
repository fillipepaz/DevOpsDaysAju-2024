# Informações sobre projeto apresentado no DevOps Days Aracaju 2024

## Estrutura da Prova de Conceito

![Alt text]([[https://assets.digitalocean.com/articles/alligator/boo.svg](https://github.com/fillipepaz/DevOpsDaysAju-2024/blob/main/arch/arch.png)](https://github.com/fillipepaz/DevOpsDaysAju-2024/blob/main/arch/arch.png) "Estrutura Apresentada")

## Versionamento da Infraestrutura
Repositório onde serão abertos os pull requests com as solicitações de provisionamento de infraestrutura.

## Backstage
Framework para construção do Internal Developer Portal.

## Módulo para provisionamento da CDN
Repositório contendo o módulo Terraform que abstrai o conjunto de recursos necessários para a entrega da estrutura para o site estático.

## Atlantis
Foi utilizada a versão 4.20 do Helm Chart do Atlantis. É possível encontrar em: [https://github.com/runatlantis/helm-charts/releases/tag/atlantis-4.20.0](https://github.com/runatlantis/helm-charts/releases/tag/atlantis-4.20.0)
Será necessário configurar um ingress com IP público para receber os Webhooks do serviço de Git escolhido.
A configuração do webhook pode ser encontrada no link: [https://www.runatlantis.io/docs/configuring-webhooks.html#github-github-enterprise](https://www.runatlantis.io/docs/configuring-webhooks.html)
