# Nessa aula vamos criar o controller da tela de person

# Arquivos


Nessa aula vamos cria esses arquivos e você pode acompanhar todas as modificações realizadas através do github.

`obs.:` cada aula será finalizada com um `commit` e um `pull request` que você poderá copiar e verificar todo o código final 🔥🤌

🗳️ `src/repositories/people/types.ts`

🗳️ `src/repositories/people/people.repository.ts`

🗳️ `src/screens/Person/person.controller.ts`

🗳️ `src/common/models/cast.credits.model.ts`

<details>
  <summary>
  Show code
  </summary>

  ```ts
  import {ShowModel} from './show.model';

export interface Character {
  href: string;
}

export interface Links {
  show: ShowModel;
  character: Character;
}

export interface Schedule {
  time: string;
  days: string[];
}

export interface Rating {
  average?: number;
}

export interface Country {
  name: string;
  code: string;
  timezone: string;
}

export interface Network {
  id: number;
  name: string;
  country: Country;
  officialSite: string;
}

export interface WebChannel {
  id: number;
  name: string;
  country?: any;
  officialSite: string;
}

export interface Externals {
  tvrage?: number;
  thetvdb?: number;
  imdb: string;
}

export interface Image {
  medium: string;
  original: string;
}

export interface Self {
  href: string;
}

export interface Previousepisode {
  href: string;
}

export interface Links2 {
  self: Self;
  previousepisode: Previousepisode;
}

export interface Embedded {
  show: ShowModel;
}

export interface CastCreditModel {
  self: boolean;
  voice: boolean;
  _links: Links;
  _embedded: Embedded;
}

  ```
</details>


# 🗳️ Código implementado na aula

[Pull Request](https://github.com/ismaelsousa/tv-maze-tutorial/pull)
