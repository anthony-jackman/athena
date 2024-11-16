# <center>ATHENA</center>

Front-end that will encompass other distance learning (DL) performance support tools (PST).

## What's in a word

Athena was the Greek goddess of wisdom, skill and war. She taught humans various skills and crafts such as weaving, and would protect heroes during war. She was said to be Zeus’ favourite daughter, so much so that he would allow her to use his weapons – even this blastastic thunderbolt! Her sacred animal was the owl. 

## Features

- ViteJS / VueJS (version 3)
- Reliance on modern CSS methods
  - CSS Grid and Flexbox
  - CSS Custom Variables 
- Full responsive design
  - Intended to be used within modern browsers on desktops and mobile devices
- Unit and E2E BDD principles
  - Includes 508 / WCAG 2.1 Level AA conformancy automatic testing/verification
  - Cypress e2e and vue component testing and node testrunner for javascript unit testing
- Full role-based CRUD operations

### This app will be developed with the following github projects:

- [Prometheus]() (Fastify v4 backend with MongoDB database)
  - Common backend to below modules and this Phanes project
  - Prometheus is planned for hosting within its own VM
- [Rhea]() (VueJS v3 front-end to process group trial events/data)
- [Panacea]() (VueJS v3 front-end to process "Help Me" events/data)
- [Hephaestus]() (VueJS v3 front-end to process course delivery events/data)
- [Muses]() (VueJS v3 front-end to process analytic events/data)
- [Pluto]() (User Management)
- [Horus]() (VueJS v3 front-end to process course details events/data)

## Authors and Contributors

- [@energeticpixels](https://github.com/EnergeticPixels): Lead programmer

## Accolades
- A more modern CSS Reset (Josh Comeau)[https://www.joshwcomeau.com/css/custom-css-reset/]
- 

## Development Specifics

### Recommended IDE Setup

- [VSCode](https://code.visualstudio.com/)
- [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) 

### Customize configuration

See [Vite Configuration Reference](https://vitejs.dev/config/).

## Project Setup

```sh
npm install
```

#### Compile and Hot-Reload for Development

```sh
npm run dev
```

#### Compile and Minify for Production

```sh
npm run build
```

#### Run Unit Tests with [Vitest](https://vitest.dev/)

```sh
npm run test:unit
```

#### Run End-to-End Tests with [Cypress](https://www.cypress.io/)

```sh
npm run test:e2e:dev
```

This runs the end-to-end tests against the Vite development server.
It is much faster than the production build.

But it's still recommended to test the production build with `test:e2e` before deploying (e.g. in CI environments):

```sh
npm run build
npm run test:e2e
```

#### Lint with [ESLint](https://eslint.org/)

```sh
npm run lint
```

