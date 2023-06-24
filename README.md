# Memoteca

Uma biblioteca de pensamentos, nelá voce pode guardar trechos de musica, citações de livros, pensamentos e suas melhores ideias, como sempre quis!

## Stack utilizada

- Angular
- Capacitor

## Aprendizados

- TypeScript
- Angular
- Json Server
- Capacitor

## Rodando localmente

- Clone o projeto

- Entre no diretório do projeto

- Instale as dependências

```bash
  npm install
```

- Entre no diretorio `backend`

- Copie o arquivo `db-template.json` e renomeie a copia dele para `db.json`
  
- Instale as dependências

```bash
  npm install
```

- Inicie o servidor `backend`

```bash
  npm start
```

- Volte para pasta principal do projeto 

- Inicie o servidor Angular

```bash
  ng serve
```


## Deploy Android

- Para fazer o deploy desse projeto primeiro faça

```bash
  ng build
```

- Copie os arquivos que ele gerar para a pasta `dist` 

- Execute o comando, para verificar e sincronizar o codigo web com o codigo nativo que será gerado

```bash
  npx cap sync
```

- Execute o comando para geração do codigo android nativo

```bash
  npx cap add android
```

- Entre no Android Studio abra a pasta gerada nele e gere um apk dele



