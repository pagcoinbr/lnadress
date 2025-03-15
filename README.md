# lnadress
Configurando parte do lnadress da BRLN. Para converter o conteúdo do invoice macaroon para base64 utilize o comando abaixo.

Copie e Cole no terminal:
```
base64 -w0 /data/lnd/data/chain/bitcoin/mainnet/invoice.macaroon > /data/lnd/data/chain/bitcoin/mainnet/invoice.macaroon.base64
```
```
sudo cat /data/lnd/data/chain/bitcoin/mainnet/invoice.macaroon.base64
```
