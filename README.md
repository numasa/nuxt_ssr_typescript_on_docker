# Base Project by TypeScript Nuxt.js (SSR) on Docker
Nuxt.js (SSRモード) / Typescript / docker のベースプロジェクト

## Version
- nuxt v2.12.2
- create-nuxt-app v2.15.0

## Nuxt App Info
- Project name: project
- Project description: My finest Nuxt.js project
- Author name: ''
- Choose programming language: TypeScript
- Choose the package manager: Yarn
- Choose UI framework: Vuetify.js
- Choose custom server framework: None
- Choose the runtime for TypeScript: @nuxt/typescript-runtime
- Choose Nuxt.js modules: Axios, Progressive Web App (PWA) Support, DotEnv
- Choose linting tools: None
- Choose test framework: None
- Choose rendering mode: Universal (SSR)
- Choose development tools: None

## Requirement
- docker
- docker-compose

## Install
1. git clone
```bash
$ git clone https://github.com/numasa/nuxt_ssr_typescript_on_docker.git
$ cd nuxt_ssr_typescript_on_docker
```

2. build & yarn install
```bash
$ docker-compose run vue yarn install
```

3. service run on localhost
```bash
$ docker-compose run --service-ports vue yarn dev
```

4. access localhost:3000 by browser
- [http://localhost:3000/](http://localhost:3000/)
