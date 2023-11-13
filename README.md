
<p align="center">
  Aplicação em Angular/TypeScript - Pokedex listagem e detalhes dos pokemons 🚀
  <br>
  <br>

  <img alt="Language count" src="https://img.shields.io/github/repo-size/alvarobraz/angular-pokedex"/>

  <a href="https://www.udemy.com/?">
    <img alt="Made by Udemy" src="https://img.shields.io/badge/made%20by-Udemy-%237519C1">
  </a>

  <a href="https://www.linkedin.com/in/alvarobraz/">
    <img alt="Made by alvarobraz" src="https://img.shields.io/badge/made%20by-alvarobraz-%237519C1">
  </a>

  <a href="https://github.com/alvarobraz/angular-pokedex/commits/main">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/alvarobraz/angular-pokedex">
  </a>

  <img alt="License" src="https://img.shields.io/github/license/alvarobraz/angular-pokedex">
</p>

---

<p align="center">
  <a href="#dart-sobre">Sobre</a> &#xa0; | &#xa0; 
  <a href="#rocket-tecnologias">Tecnologias</a> &#xa0; | &#xa0;
  <a href="#estrutura">Estrurura</a> &#xa0; | &#xa0;
  <a href="#white_check_mark-requerimentos">Requerimentos</a> &#xa0; | &#xa0;
  <a href="#checkered_flag-começando">Começando</a>
</p>

<br>

## :dart: Sobre ##

Aplicação em Angular/TypeScript baseada no consumo de uma api do famoso desenho Pokemon, nesta aplicação foi usado os conceito de módulos, componetização, serviços, injeção de dependência,  data binding, sistema de roteamento, observables e RxJS para trabalhar eficientemente com assincronismo, eventos e comunicação entre componentes!

## :rocket: Tecnologias ##

As seguintes tecnologias foram utilizadas no projeto:

- [Angular](https://angular.io/docs)
- [TypeScript](https://www.typescriptlang.org/)

## Estrutura ##
```
.
├── angular.json
├── karma.conf.js
├── LICENSE
├── package.json
├── package-lock.json
├── README.md
├── src
│   ├── app
│   │   ├── app.component.ts
│   │   ├── app.module.ts
│   │   ├── app-routing.module.ts
│   │   ├── pages
│   │   │   ├── details
│   │   │   │   ├── details.component.html
│   │   │   │   ├── details.component.scss
│   │   │   │   └── details.component.ts
│   │   │   ├── home
│   │   │   │   ├── home.component.html
│   │   │   │   ├── home.component.scss
│   │   │   │   └── home.component.ts
│   │   │   ├── pages.module.ts
│   │   │   └── routing.module.ts
│   │   ├── service
│   │   │   └── poke-api.service.ts
│   │   └── shared
│   │       ├── poke-header
│   │       │   ├── poke-header.component.html
│   │       │   ├── poke-header.component.scss
│   │       │   └── poke-header.component.ts
│   │       ├── poke-list
│   │       │   ├── poke-list.component.html
│   │       │   ├── poke-list.component.scss
│   │       │   └── poke-list.component.ts
│   │       ├── poke-search
│   │       │   ├── poke-search.component.html
│   │       │   ├── poke-search.component.scss
│   │       │   └── poke-search.component.ts
│   │       └── shared.module.ts
│   ├── assets
│   │   ├── bg
│   │   │   └── background-list-pokemons.svg
│   │   ├── error.png
│   │   ├── icons
│   │   │   └── search.svg
│   │   ├── logo.svg
│   │   └── pokemon.png
│   ├── config-scss
│   │   ├── animation.scss
│   │   ├── btn.scss
│   │   ├── rem-calc.scss
│   │   ├── reset.scss
│   │   └── variables.scss
│   ├── environments
│   │   ├── environment.prod.ts
│   │   └── environment.ts
│   ├── favicon.ico
│   ├── index.html
│   ├── main.ts
│   ├── polyfills.ts
│   ├── styles.scss
│   └── test.ts
├── tsconfig.app.json
├── tsconfig.json
└── tsconfig.spec.json


```

## :white_check_mark: Requerimentos ##

- [Angular](https://v14.angular.io/docs)
- [Node.js](https://nodejs.org/docs/latest-v14.x/api/cli.html)

## :checkered_flag: Começando ##

```bash
# Clone this project
$ git clone https://github.com/alvarobraz/angular-pokedex

# Access
$ cd angular-pokedex

# Install dependencies
$ npm install

# Run the project
$ ng server

# The server will initialize in the <http://localhost:4200/>
```
