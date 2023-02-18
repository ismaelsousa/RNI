# Nessa aula vamos criar o componente Icon que será usado em todo o app

A ideia do compoente Icon é criar um componente que contém todos os ícones da aplicação.

Nessa aula também conhecemos o `Image` que é para lidar com imagens sejam locais ou da internet.

# Branch

Crie uma nova branch para a aula `rn-09`

# Arquivos

Nessa aula vamos cria esses arquivos e você pode acompanhar todas as modificações realizadas através do github.

`obs.:` cada aula será finalizada com um `commit` e um `pull request` que você poderá copiar e verificar todo o código final 🔥🤌


🗳️ `src/common/components/Icon/types.ts`

🗳️ `src/common/components/Icon/styles.ts`

🗳️ `src/common/components/Icon/index.tsx`

🗳️ `src/@types/image.d.ts`
```js
declare module '*.png';
```

🗳️ `src/common/constants/icons.ts`

```js

import home from '../../assets/icons/home/Vector.png';
import favorite from '../../assets/icons/favorite/Vector.png';
import search from '../../assets/icons/search/Vector.png';
import magnify from '../../assets/icons/magnify/Vector.png';
import picture from '../../assets/icons/picture/Vector.png';
import arrowLeft from '../../assets/icons/arrow-left/Vector.png';
import menuDown from '../../assets/icons/menu-down/menu-down.png';
import menuUp from '../../assets/icons/menu-up/menu-up.png';
import close from '../../assets/icons/close/Vector.png';
import star from '../../assets/icons/star/Vector.png';
import starOutline from '../../assets/icons/star-outline/Vector.png';
import person from '../../assets/icons/person/account-circle.png';
import inbox from '../../assets/icons/inbox/Vector.png';
import noResults from '../../assets/icons/no-results/Vector.png';
import backspace from '../../assets/icons/backspace/backspace.png';

export type NameIconTypes =
  | 'home'
  | 'favorite'
  | 'search'
  | 'magnify'
  | 'picture'
  | 'arrowLeft'
  | 'menuDown'
  | 'menuUp'
  | 'close'
  | 'star'
  | 'starOutline'
  | 'person'
  | 'inbox'
  | 'noResults'
  | 'backspace';

export default {
  home,
  favorite,
  search,
  magnify,
  picture,
  arrowLeft,
  menuDown,
  menuUp,
  close,
  star,
  starOutline,
  person,
  inbox,
  noResults,
  backspace,
};


```

# 🗳️ Código implementado na aula

[Pull Request](https://github.com/ismaelsousa/tv-maze-tutorial/pull/6)
