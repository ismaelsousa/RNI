# Nessa aula vamos criar o componente EpisodeCard que será usado em todo o app

A ideia do compoente EpisodeCard é mostrar o episódios completo.

[`TV MAZE API`](https://www.tvmaze.com/api)

`Example:` https://api.tvmaze.com/singlesearch/shows?q=girls&embed=episodes

## Tool json2ts

Essa ferramenta transforma o `json` em `ts`

[json2ts](http://json2ts.com/)

# Arquivos

Nessa aula vamos cria esses arquivos e você pode acompanhar todas as modificações realizadas através do github.

`obs.:` cada aula será finalizada com um `commit` e um `pull request` que você poderá copiar e verificar todo o código final 🔥🤌

🗳️ `src/common/constants/mocks/episode.mock.ts`

<details>

<summary>
Show code
</summary>

```js
export const episodeMocked = {
  id: 1,
  url: 'https://www.tvmaze.com/episodes/1/under-the-dome-1x01-pilot',
  name: 'Pilot',
  season: 1,
  number: 1,
  type: 'regular',
  airdate: '2013-06-24',
  airtime: '22:00',
  airstamp: '2013-06-25T02:00:00+00:00',
  runtime: 60,
  rating: {
    average: 7.7,
  },
  image: {
    medium:
      'https://static.tvmaze.com/uploads/images/medium_landscape/1/4388.jpg',
    original:
      'https://static.tvmaze.com/uploads/images/original_untouched/1/4388.jpg',
  },
  summary:
    "<p>When the residents of Chester's Mill find themselves trapped under a massive transparent dome with no way out, they struggle to survive as resources rapidly dwindle and panic quickly escalates.</p>",
  _links: {
    self: {
      href: 'https://api.tvmaze.com/episodes/1',
    },
  },
};

```
</details>

🗳️ `src/common/models/episode.model.ts`

<details>

<summary>
Show code
</summary>

```ts

export interface Rating {
  average: number;
}

export interface Image {
  medium: string;
  original: string;
}

export interface Self {
  href: string;
}

export interface Links {
  self: Self;
}

export interface EpisodeModel {
  id: number;
  url: string;
  name: string;
  season: number;
  number?: number;
  type: string;
  airdate: string;
  airtime: string;
  airstamp: Date;
  runtime: number;
  rating: Rating;
  image?: Image;
  summary?: string;
  _links: Links;
}

```

</details>

🗳️ `src/common/utils/html.ts`

🗳️ `src/common/utils/message.ts`

🗳️ `src/common/components/EpisodeCard/types.ts`

🗳️ `src/common/components/EpisodeCard/styles.ts`

🗳️ `src/common/components/EpisodeCard/index.tsx`


# 🗳️ Código implementado na aula

[Pull Request](https://github.com/ismaelsousa/tv-maze-tutorial/pull/13)
