# Finanças PF/PJ

App de controle financeiro pessoal (PF) e de pessoa jurídica (PJ), com cálculo automático de impostos (DAS, INSS) e pró-labore. PWA instalável no celular, funciona offline.

## Rodar localmente

```bash
node server.js
```

Abra http://localhost:3000

## Deploy

Feito via Railway, apontando para este repositório. O `server.js` serve os arquivos estáticos (`index.html`, `manifest.json`, `sw.js`, `icons/`) na porta definida por `PORT`.
