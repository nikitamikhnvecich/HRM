# Curriculum Vitae Project (Task #10 Innowise Internship)

### [Task Details](https://innowise-group.atlassian.net/wiki/spaces/~9373156/pages/2617180325/Curriculum+Vitae+Project)

### Developers:

- [Nikita Prihodko](https://github.com/kirpichev228)
- [Alexander Yablonsky](https://github.com/elus1vee)
- [Nikita Mikhnevich](https://github.com/Elvinsky)

### Stack

- VueJS (3.x)
- TypeScript
- Pinia
- Vuetify
- SCSS
- Apollo Client + GraphQL

### Project Installation & Launching

- `git init`
- `git clone <repo url>`
- `npm install`
- `npm run dev`
- Follow port you are given after this

### Lint with [ESLint](https://eslint.org/)

`npm run lint`

### Format with [Prettier](https://prettier.io/)

`npm run format`

### Directories

- **root** - configuration files
- **patches** - i18n TS patch
- **public** - auto created directory with assets
- **src**
  - **assest** - assets used in project
  - **components** - Vue application components. _Has nested directories with components distributed in groups_
  - **consts** - constant values
  - **i18n** - localization config and JSON-schemas
  - **router** - vue-router file
  - **service** - Apollo Client services (Mutations & Queries)
  - **stores** - Pinia store files
  - **types** - TS interfaces & literals
  - **utils** - utility TS functions
  - **views** - Vue components for router rendering
  - **App.vue** - starting point of Vue app
  - **apollo.provider.ts** - Apollo Client config
  - **main.ts** - starting point of the project
