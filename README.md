# Encoding tools by Bout de code

![https://boutdecode.fr](https://boutdecode.fr/img/logo.png)

[Bout de code](https://boutdecode.fr) - Développement de site internet et blog avec de vrais morceaux de codes, simples, élégants, utiles (parfois) et surtout sans fioriture.

## Installation

```shell
$ npm install @boutdecode/enconding
```

## Yion plugin

For yion : 

```javascript
const { createApp, createServer } = require('@boutdecode/yion')
const encodingPlugin = require('@boutdecode/encoding/yion/encoding-plugin')

const app = createApp()
const server = createServer(app, [encodingPlugin])

server.listen(8080)
```

## Tests

```shell
$ npm run test
```
