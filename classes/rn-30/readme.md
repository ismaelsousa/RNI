# Nessa aula vamos criar os repositórios para o controller da tela de search

# Arquivos


Nessa aula vamos cria esses arquivos e você pode acompanhar todas as modificações realizadas através do github.

`obs.:` cada aula será finalizada com um `commit` e um `pull request` que você poderá copiar e verificar todo o código final 🔥🤌


🗳️ `src/repositories/search/peopleByText/peopleByText.repository.ts`

🗳️ `src/repositories/search/peopleByText/types.ts`

🗳️ `src/repositories/search/showsByText/showsByText.repository.ts`

🗳️ `src/repositories/search/showsByText/types.ts`

🗳️ `src/common/models/showByText.model.ts`

🗳️ `src/common/models/peopleByText.model.ts`

🗳️ `src/common/models/person.model.ts`

<details>
<summary>
Show code
</summary>

```ts
export interface Country {
  name: string;
  code: string;
  timezone: string;
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

export interface PersonModel {
  id: number;
  url: string;
  name?: string;
  country?: Country;
  birthday?: string;
  deathday?: string;
  gender: string;
  image?: Image;
  updated: number;
  _links: Links;
}

```

</details>


# 🗳️ Código implementado na aula

[Pull Request](https://github.com/ismaelsousa/tv-maze-tutorial/pull)
