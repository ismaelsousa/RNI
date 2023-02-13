# Nessa aula vamos criar o tema para o nosso aplicativo. 

<p align='center'>
  
<img align='center' src='https://user-images.githubusercontent.com/28990749/218275230-e064d30f-81af-479a-a497-205bf36cef60.png' width='100px' />
<p/>



O styled-component oferece uma forma muito boa de trabalhar com temas no nosso app, então vamos definir cores e espaçamentos do nosso app para que seja padrão por toda aplicação.

### Extensão 

Adicione a extensão do styled-components para o seu vscode

[Link para a extensão](https://marketplace.visualstudio.com/items?itemName=styled-components.vscode-styled-components)

Para facilitar copie as cores abaixo que foram retiradas do [Figma](https://www.figma.com/file/0jGlxxKJD82RpG9FTRfecD/TVMaze?node-id=2%3A7&t=VtU8K4Mm3wopyNpk-0)

```
export const primary = '#000000';
export const secondary = '#171717';
export const onSecondary = '#FDFDFD';
export const caption = '#9A9A9A';
export const surface = '#323232';
export const brand = '#3C948B';
export const alert = '#943C3C';

```

# Branch

Crie uma nova branch para a aula `rn-04`

# Dependências de desenvolvimento

```bash
npm i @types/styled-components@5.1.13 @types/styled-components-react-native@5.1.1  --save-dev
```

# Arquivos

Nessa aula vamos cria esses arquivos e você pode acompanhar todas as modificações realizadas através do github.

`obs.:` cada aula será finalizada com um `commit` e um `pull request` que você poderá copiar e verificar todo o código final 🔥🤌


🗳️ `src/common/constants/styles/colors.ts`

🗳️ `src/@types/styled.d.ts`

🗳️ `src/common/constants/styles/theme/defaultTheme.ts`

🗳️ `src/App.tsx` 

# 🗳️ Código implementado na aula

[Pull Request #1](https://github.com/ismaelsousa/tv-maze-tutorial/pull/1)
