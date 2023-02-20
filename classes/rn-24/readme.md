# Nessa aula vamos tratar os dados do show para mostar na tela de detalhes e conhecer o interceptor

O interceptor serve para interceptar requisições sejam elas request ou reponse.

```js

client.interceptors.request.use((config) => {
  console.log("💻 Request: ", `${config.baseURL}${config.url}`);

  return config;
});

```

# Arquivos

Nessa aula vamos cria esses arquivos e você pode acompanhar todas as modificações realizadas através do github.

`obs.:` cada aula será finalizada com um `commit` e um `pull request` que você poderá copiar e verificar todo o código final 🔥🤌

🗳️ `src/repositories/api.ts`

🗳️ `src/screens/Detail/detail.controller.tsx`

🗳️ `src/screens/Detail/detail.view.tsx`


# 🗳️ Código implementado na aula

[Pull Request](https://github.com/ismaelsousa/tv-maze-tutorial/pull)
