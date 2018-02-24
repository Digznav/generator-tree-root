## Project structure


### Basic

```
/
├── changelog/
├── tools/
├── .editorconfig



├── common/
├── dist/
├── examples/
├── grunt/
├── preview/
├── public/
├── scripts/
└── src/
    ├── css/
    ├── data/
    ├── emails/
    ├── img/
    ├── partials/
    └── scss/
        ├── modules/
        └── partials/
```







New repository

Add:
- `.editorconfig`
- `.gitignore`
- `.npmignore`: technically this is only required when the package will be published to npm but this will keep the dependencies clean from dev dependencies and define which files are really needed in distribution
- `.npmscripts.js`: compare Shared, maple and react
- `.nvmrc`: node v8
- `.prettierignore`:
    - basic: Maple
    - extended: Shared

- `package.json`
    - Create it with `npm init`. If it is a private package use: `npm init --scope=justia`
    - Globally install `sort-package-json` to sort all properties of the file.

JS Projects
- `.eslintignore`: only if needed
- `.eslintrc.json`
    - 2 tabs: copy maple-js
    - 4 tabs: copy Ash
- `webpack.config.js`

SASS projects
- `.bsconfig.js`
- `.stylelintrc.json`
    - 2 tabs: copy maple-sass
    - 4 tabs: copy Shared

With Grunt
- `grunt/`
- `Gruntfile.js`


