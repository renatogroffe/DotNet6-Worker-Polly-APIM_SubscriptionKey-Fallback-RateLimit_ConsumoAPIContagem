# DotNet6-Worker-Polly-APIM_SubscriptionKey-Fallback-RateLimit_ConsumoAPIContagem
Exemplo de consumo em um Worker Service criado com .NET 6 de uma API REST (contagem de acessos), utilizando para isto um Header com uma Subscription Key do Azure API Management e a biblioteca Polly com o padrão Fallback (retornando um valor default após se atingir um limite de requisições enviadas - Rate Limit).

**OBSERVAÇÃO**: A API utilizada foi disponibilizada no **Docker Hub** como uma imagem pública (**renatogroffe/apicontagem-appinsights-dotnet6**) e foi exposta através de um endpoint configurado com o **Azure API Management**.
