## Sobre o projeto

Esse projeto surgiu a partir da ideia de converter o [Coinpaprika BR Bot](https://t.me/CppBrBot) do Telegram para o WhatsApp, só que após terminar a versão de WhatsApp eu pensei: e se talvez eu fizer uma versão para Discord? Então acabou tendo esse resultado. Nesse bot é utilizado a biblioteca [discord.js](https://discord.js.org/#/) para a criação do mesmo e na crecagem de cotação utilizamos a API da [Coinpaprika](https://api.coinpaprika.com/).

## Funcionalidades

| Funcionalidade  | Status |
| ------------- | ------------- |
| !price [símbolo] [quantia] = Retorna a cotação do simbolo escolhido. QUANTIA opcional.  | ✅  |
| !convert [valor] [base] [cotação] = Retorna a cotação total de uma moeda na cotação determinada. | ✅  |
| !buy [quantidade] [base] [cotação] [spread] = Retorna a quantia de moedas a ser compradas com agil para baixo.  | ✅  |
| !sell [quantidade] [base] [cotação] [spread] = Retorna a quantia de moedas a ser vendida com agil para cima. | ✅ |
| !brlbuy [quantidade] [cripto] [spread] = Retorna a quantidade de moedas a serem compradas a partir da quantidade de reais e ágil para baixo.  | ✅  |
| !brlsell [quantidade] [cripto] [spread] = Retorna a quantidade de moedas a serem vendidas a partir da quantidade de reais e ágil para cima. | ✅ |

## Versões

* [WhatsApp](https://github.com/SmookeyDev/coinpaprika-whatsapp-bot)
* [Telegram](https://github.com/marcosnunesmbs/coinpaprika-br-bot/)
* [Discord](https://github.com/SmookeyDev/coinpaprika-discord-bot)

## Créditos

* [Ícaro Sant'Ana](https://t.me/SmookeyDev) - Versão de WhatsApp e Discord.
* [Marcos Nunes](https://github.com/marcosnunesmbs) - Versão de Telegram.
