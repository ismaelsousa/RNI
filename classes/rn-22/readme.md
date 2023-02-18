# Nessa aula vamos criar um componente local para a tela de detalhes

Nessa aula conhecemos o [`Modal`](https://reactnative.dev/docs/modal) do react native

# Arquivos

Nessa aula vamos cria esses arquivos e você pode acompanhar todas as modificações realizadas através do github.

`obs.:` cada aula será finalizada com um `commit` e um `pull request` que você poderá copiar e verificar todo o código final 🔥🤌


🗳️ `src/common/constants/mocks/season.mock.ts`

<details>
<summary>
Show code
</summary>

```js
export const seasonMocked = {
  id: 1,
  url: 'https://www.tvmaze.com/seasons/1/under-the-dome-season-1',
  number: 1,
  name: '',
  episodeOrder: 13,
  premiereDate: '2013-06-24',
  endDate: '2013-09-16',
  network: {
    id: 2,
    name: 'CBS',
    country: {
      name: 'United States',
      code: 'US',
      timezone: 'America/New_York',
    },
    officialSite: 'https://www.cbs.com/',
  },
  webChannel: null,
  image: {
    medium:
      'https://static.tvmaze.com/uploads/images/medium_portrait/24/60941.jpg',
    original:
      'https://static.tvmaze.com/uploads/images/original_untouched/24/60941.jpg',
  },
  summary: '',
  _links: {
    self: {
      href: 'https://api.tvmaze.com/seasons/1',
    },
  },
};

```

</details>

🗳️ `src/common/models/season.model.ts`

🗳️ `src/screens/Detail/localComponents/SeasonsModal/index.tsx`

🗳️ `src/screens/Detail/localComponents/SeasonsModal/styles.ts`

🗳️ `src/screens/Detail/localComponents/SeasonsModal/types.ts`

# 🗳️ Código implementado na aula

[Pull Request](https://github.com/ismaelsousa/tv-maze-tutorial/pull/19)
