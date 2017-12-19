CryptoNoter Docker
==================

Start [CryptoNoter](github.com/cryptonoter/CryptoNoter) in a docker container.

See [www.cryptonoter.com](www.cryptonoter.com) for more info.


## Environment Variables

** DOMAIN ** defaults to `localhost`

** POOL ** defaults to `pool.cryptonoter.com:1111`

** ADDR ** (REQUIRED) the XMR or ETN address to send payments

** PASS ** (REQUIRED) the password for CryptoNoter

## Example

```
docker run --rm -it -p 7777:7777 -e ADDR=<xmr wallet> -e PASS=<password> CryptoNoter
```
