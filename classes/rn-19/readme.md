# Nessa aula vamos tipar e usar o nosso serviço http

A gente vai usar a api do `TV MAZE`

`Endpoint:  https://api.tvmaze.com/shows?page=1`

Nessa aula conhecemos o [`useEffect`](https://beta.reactjs.org/reference/react/useEffect), o [`useCallback`](https://beta.reactjs.org/reference/react/useCallback) e o [`MVVM`](https://youtu.be/RGRfXh54d9U)

# Arquivos

Nessa aula vamos cria esses arquivos e você pode acompanhar todas as modificações realizadas através do github.

`obs.:` cada aula será finalizada com um `commit` e um `pull request` que você poderá copiar e verificar todo o código final 🔥🤌



🗳️ `src/common/models/show.model.ts`

<details>
<summary>
Show code
</summary>

```ts
export interface Schedule {
  time: string;
  days: any[];
}

export interface Rating {
  average?: any;
}

export interface WebChannel {
  id: number;
  name: string;
  country?: any;
  officialSite: string;
}

export interface Externals {
  tvrage?: any;
  thetvdb?: any;
  imdb: string;
}

export interface Self {
  href: string;
}

export interface Links {
  self: Self;
}

export interface ShowModel {
  id: number;
  url: string;
  name: string;
  type: string;
  language: string;
  genres: string[];
  status?: 'Running' | 'Ended';
  runtime?: any;
  averageRuntime?: any;
  premiered?: any;
  ended?: any;
  officialSite?: any;
  schedule: Schedule;
  rating: Rating;
  weight: number;
  network?: any;
  webChannel: WebChannel;
  dvdCountry?: any;
  externals: Externals;
  image?: {
    medium: string;
    original: string;
  };
  summary?: string;
  updated: number;
  _links: Links;
}

```
</details>

🗳️ `src/repositories/shows/shows.repository.ts`

🗳️ `src/screens/Home/home.controller.tsx`


# 🗳️ Código implementado na aula

[Pull Request](https://github.com/ismaelsousa/tv-maze-tutorial/pull/15)
