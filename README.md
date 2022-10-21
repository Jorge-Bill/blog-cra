<p align="center">
  <a href="https://jorgemendes.com.br/">
    <img src="https://raw.githubusercontent.com/Jorge-Bill/Jorge-Bill/master/assets/jorge.png">
  </a>
</p>

## 👾 Structure base Custom CRA

---

## 🚀 Project Structure

This project structure a web app with great organization, made to be the base template for other apps.

Stack and resources used on this structure creation.

    .
    ├── React CRA
    ├── prop-types
    ├── Eslint + eslint-config-airbnb + prettier
    ├── Plop component generator
    ├── Styled-components
    ├── Styled-icons
    ├── Styled-media-query
    ├── React-router-dom
    ├── Jest
    ├── Dotenv
    ├── Husky
    ├── Commitizen

## 🛠 Scripts

| Action                              | Usage (npm)        | Usage (yarn)    |
| ----------------------------------- | ------------------ | --------------- |
| Start development mode              | `npm start`        | `yarn start`    |
| Buold the app                       | `npm run build`    | `yarn build`    |
| Generate new components             | `npm run generate` | `yarn generate` |
| Execute the Jest test suite         | `npm run test`     | `yarn test`     |
| Eject the app\*                     | `npm run eject`    | `yarn eject`    |
| commit with Husky and commitizen\*  | `npm run commit`   | `yarn commit`   |
| use prettier to verify files on app | `npm run lint`     | `yarn lint`     |
| use prettier to format files on app | `npm run format`   | `yarn format`   |

- `yarn eject` - \* This is a one-way operation. Once you eject, you can’t go back - remove the single build dependency from your project.
- `yarn commit` - \* commit with Husky and commitizen | type `git commit` works too.

## ⚙️ How to use the structure

For using the structure as a second origin use the follow lines:

- `git remote add structure git@github.com:Jorge-Bill/blog-cra.git`

On first time pull request

- `git pull structure HEAD:master --allow-unrelated-histories`

After the first pull request

- `git pull structure HEAD:master`

## 💾 SET Husky hoooks

- `yarn husky install`

If any of yours hook is not working, you can make them execute with:

- `yarn husky add .husky/hook-name`

## 🖥 ENV VARIABLES

.env variables used for Seo component.

- `REACT_APP_TITLE=''`
- `REACT_APP_DESCRIPTION=''`
- `REACT_APP_LANG=''`
- `REACT_APP_IMAGE=''`
- `REACT_APP_AUTHOR=''`
- `REACT_APP_SITE_URL=''`

---
