# Arquivo de documentação

## Instalações

Instale o typescript:
npm install typescript --save-dev


Crie um arquivo tsconfig.json na raiz do seu projeto e configure as opções necessárias para o TypeScript:

{
  "compilerOptions": {
    "target": "es6",
    "module": "commonjs",
    "outDir": "./dist",
    "esModuleInterop": true,
    "sourceMap": true
  },
  "include": ["src/**/*"],
  "exclude": ["node_modules", "**/*.spec.ts"]
}

## Transpilando projeto

Para transpilar o projeto é necessário usar o comando no terminal: tsc

## Execução

Para executar o projeto como typescript use o comando: npm run dev
