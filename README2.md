# vendas-online-web

## Documentação

React  
https://react.dev/

Vite  
https://vite.dev/guide/

Prettier  
https://prettier.io/docs/en/options.html

## Bibliotecas e pluggins

### Padronização

```
npm install --save-dev @typescript-eslint/eslint-plugin @typescript-eslint/parser eslint eslint-config-prettier eslint-plugin-import eslint-plugin-prettier eslint-plugin-react eslint-plugin-simple-import-sort pre-commit prettier
```

` npm install --save-dev pre-commit`

## Comandos

Rodar projeto  
`npm run dev`

Antes de subir o commit para corrigir a formatação do código  
 `npm rum lint`

## Arquivos para inserir no projeto

### Na raiz

Arquivos  
`.eslintrc.js`  
`.prettierrc.js`

Pastas  
`.vscode` tirar do GitIgnore dentro incluir  
`settings.json`

## Alteraçõe no projeto inicial Vitte

- package.json  
  Remover para eslint funcionar corretamente  
  `"type": "module",`  
  `"private": true,`
