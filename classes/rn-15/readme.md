# Nessa aula vamos criar o componente EpisodeCover que será usado em todo o app

A ideia do compoente EpisodeCover é mostrar as capas dos episódios.

[`TV MAZE API`](https://www.tvmaze.com/api)

`Example:` https://api.tvmaze.com/singlesearch/shows?q=girls&embed=episodes

Dentro de cada episódio tem a proprietade de `image` dessa forma:

```json
{
  "image": {
    "medium": "https://static.tvmaze.com/uploads/images/medium_landscape/15/38639.jpg",
    "original": "https://static.tvmaze.com/uploads/images/original_untouched/15/38639.jpg"
  }
}

```

Essa imagem segue o aspect ratio de `16/9`


Crie uma nova branch para a aula `rn-15`

# Arquivos

Nessa aula vamos cria esses arquivos e você pode acompanhar todas as modificações realizadas através do github.

`obs.:` cada aula será finalizada com um `commit` e um `pull request` que você poderá copiar e verificar todo o código final 🔥🤌


🗳️ `src/common/components/EpisodeCover/types.ts`

🗳️ `src/common/components/EpisodeCover/styles.ts`

🗳️ `src/common/components/EpisodeCover/index.tsx`


# 🗳️ Código implementado na aula

[Pull Request](https://github.com/ismaelsousa/tv-maze-tutorial/pull/12)
