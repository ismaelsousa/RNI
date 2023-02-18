# Nessa aula vamos criar o componente ShowCover que será usado em todo o app

Vamos conhecer o [`useWindowDimensions`](https://reactnative.dev/docs/usewindowdimensions), [`useMemo`](https://beta.reactjs.org/reference/react/useMemo), e o [`memo`](https://beta.reactjs.org/reference/react/memo)

A ideia do compoente ShowCover é mostrar as capas dos filmes e para isso já vamos conhecer a API do TV MAZE.

[`TV MAZE API`](https://www.tvmaze.com/api)

Nessa API temos o endpoint para buscar shows e como resposta temos a lista de show com várias características.

`Example:` https://api.tvmaze.com/shows?page=1

Dentro de cada show tem a proprietade de `image` dessa forma:

```json
{
  "image": {
      "medium": "https://static.tvmaze.com/uploads/images/medium_portrait/1/4600.jpg",
      "original": "https://static.tvmaze.com/uploads/images/original_untouched/1/4600.jpg"
    },
}

```

Essa imagem seguem o aspect ratio de `9/12.5`

Para conseguir o aspect ratio de determinada imagem basta dividir a altura pela largura.

`r` = `9/12.5` = `0,72` 


Crie uma nova branch para a aula `rn-13`

# Arquivos

Nessa aula vamos cria esses arquivos e você pode acompanhar todas as modificações realizadas através do github.

`obs.:` cada aula será finalizada com um `commit` e um `pull request` que você poderá copiar e verificar todo o código final 🔥🤌


🗳️ `src/common/components/ShowCover/types.ts`

🗳️ `src/common/components/ShowCover/styles.ts`

🗳️ `src/common/components/ShowCover/index.tsx`


# 🗳️ Código implementado na aula

[Pull Request](https://github.com/ismaelsousa/tv-maze-tutorial/pull/11)
