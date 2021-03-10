### <a name="top"></a>

<h1 align="center">
  <a href="https://gobarber.desenvolvendosistemas.dev.br">
    <img alt="GoBarber logotipo" src="src/assets/logo.svg" />
  </a>
</h1>

<h5 align="center">
  💈 GoBarber mob app , a project developed to offer barber shop scheduling.
</h5>

<p align="center">
  <!-- <a href="#art-app-ui">🎨 App UI</a>&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp; -->
  <a href="#flying_saucer-technologies">🛸 Technologies</a>&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#warning-prerequisites">⚠️ Prerequisites</a>&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;
  <a href="#grey_question-how-to-use">❔ How To Use</a>&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#bookmark-badges">🔖 Badges</a>&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#closed_lock_with_key-license">🔐 License</a>
</p>

<!-- <br> -->

<!-- ## :art: App UI -->

<!-- <br> -->

<p align="center">
  <img alt="GoBarber background image" src="src/assets/mockuper (1).png" width="100%" />
</p>

## [🔝](#top) Techs :flying_saucer:

This project was developed at the [RocketSeat GoStack Bootcamp 11](https://rocketseat.com.br) with the following technologies:

-  [Axios](https://github.com/axios/axios)
-  [Commitlint](https://github.com/conventional-changelog/commitlint)
-  [Commitizen](https://github.com/commitizen/cz-cli)
-  [Date-fns](https://date-fns.org/)
-  [Husky](https://github.com/typicode/husky)
-  [Jest](https://jestjs.io/)
-  [ReactJS](https://reactjs.org/)
-  [React Native](https://reactnative.dev/)
-  [React Native Gesture Handler](https://github.com/software-mansion/react-native-gesture-handler)
-  [React Native Image Picker](https://github.com/react-native-image-picker/react-native-image-picker)
-  [React Native Vector Icons](https://github.com/oblador/react-native-vector-icons)
-  [Semantic-release](https://semantic-release.gitbook.io/semantic-release/)
-  [Styled Components](https://www.styled-components.com/)
-  [TypeScript](https://www.typescriptlang.org/)
-  [Unform](https://unform.dev/)
-  [VS Code][vc] with [ESLint][vceslint], [EditorConfig][vceditconfig] & [Prettier][vcprettier]
-  [Yup](https://github.com/jquense/yup)

## [🔝](#top) Prerequisites :warning:

In order to use and test the mobile app on a simulator or on your physical smartphone, you should've already setup the development environment for React Native applications. You can follow the following article (PT-BR) to setup your environment: [React Native Environment (Android/iOS)](https://docs.rocketseat.dev/ambiente-react-native/introducao).

And also, firstly i recommend that you access and run the backend repository for a complete experience. <br>
_Or go to [**gobarber.desenvolvendosistemas.dev.br**](https://gobarber.desenvolvendosistemas.dev.br/) to see the web project in a production environment._

<a href="https://github.com/caiohenrique-developer/node-deploy">
  <img width="350px" alt="GoBarber back-end repository" src="https://github-readme-stats.vercel.app/api/pin/?username=caiohenrique-developer&repo=node-deploy&theme=dark" />
</a>

## [🔝](#top) How To Use :grey_question:

To clone and run this application locally, you'll need [Git](https://git-scm.com), [Node.js v10.16][nodejs] or higher + [Yarn v1.13][yarn] or higher installed on your computer.

<details open>
  <summary>Hit me to toggle collapse: 🕹️🤏</summary>

  _From your `command line` follow these steps..._

  ```bash
  # Clone the project
  $ git clone https://github.com/caiohenrique-developer/react-native-deploy 'GoBarber Mob' && cd 'GoBarber Mob'

  # Install dependencies
  $ yarn
  # or
  $ npm i

  # ** Simulator **

  # If you want to run the project on a simulador like Android Studio or Genymotion, start the react-native server as it is
  $ yarn start
  # or
  $ npm start

  # On another terminal, install the app on your simulator
  # Start the project using the command below for Android devices
  $ yarn android
  # or
  $ npm android

  # or

  # Start the project using the command below for iOS devices
  $ yarn ios --simulator="iPhone XS Max"
  # or
  $ npm ios --simulator="iPhone XS Max"

  # ** Physical Smartphone **

  # If you want to run the project on your physical smartphone, change the baseURL on src/services/api.js to your machine's ethernet adapter IP. Use the ethernet adapter IP if you're on a cable connection or the WiFi adapter IP if you're on a wireless conecction.
  # After changing the baseURL, start the react-native server
  $ yarn start
  # or
  $ npm start

  # On another terminal, install the app on your physical smartphone
  # Start the project using the command below for Android devices
  $ yarn android
  # or
  $ npm android

  # Start the project using the command below for iOS devices
  $ yarn ios
  # or
  $ npm ios

  # Very well, now you can enjoy this project ;)
  ```

  + <details>
      <summary>See also: 🕹️🤏</summary>

      #### API

      <a href="https://github.com/caiohenrique-developer/node-deploy">
        <img width="350px" alt="GoBarber back-end repository" src="https://github-readme-stats.vercel.app/api/pin/?username=caiohenrique-developer&repo=node-deploy&theme=dark" />
      </a>

      #### WEB

      <a href="https://github.com/caiohenrique-developer/react-deploy">
        <img width="350px" alt="GoBarber front-end repository" src="https://github-readme-stats.vercel.app/api/pin/?username=caiohenrique-developer&repo=react-deploy&theme=dark" />
      </a>
    </details>
</details>

<p align="center">
  <img alt="GoBarber background image" src="src/assets/New.svg" width="700" />
</p>

## [🔝](#top) Badges :bookmark:

<p align="center">
  <img alt="GitHub Language Count" src="https://img.shields.io/github/languages/count/caiohenrique-developer/react-native-deploy">

  <img alt="GitHub Top Language" src="https://img.shields.io/github/languages/top/caiohenrique-developer/react-native-deploy">

  <a href="https://www.codacy.com/app/caiohenrique-developer/react-native-deploy?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=caiohenrique-developer/react-native-deploy&amp;utm_campaign=Badge_Grade">
    <img alt="Codacy Grade" src="https://img.shields.io/codacy/grade/4f87fc059ec846118f2ef2950200b13a.svg">
  </a>

  <a href="https://github.com/caiohenrique-developer/react-native-deploy/commits/master">
    <img alt="GitHub Last Commit" src="https://img.shields.io/github/last-commit/caiohenrique-developer/react-native-deploy">
  </a>

  <a href="https://github.com/caiohenrique-developer/react-native-deploy/releases">
    <img alt="GitHub Releases" src="https://img.shields.io/github/release-date/caiohenrique-developer/react-native-deploy">
  </a>

  <br>

  <a href="https://github.com/caiohenrique-developer/react-native-deploy/tags">
    <img alt="GitHub Tags" src="https://img.shields.io/github/package-json/v/caiohenrique-developer/react-native-deploy/master">
  </a>

  <a href="https://github.com/caiohenrique-developer/react-native-deploy/issues">
    <img alt="Repository issues" src="https://img.shields.io/github/issues/caiohenrique-developer/react-native-deploy">
  </a>

  <img alt="Repository Size" src="https://img.shields.io/github/repo-size/caiohenrique-developer/react-native-deploy">

  <img alt="GitHub License" src="https://img.shields.io/github/license/caiohenrique-developer/react-native-deploy">

  <a href="https://github.com/semantic-release/semantic-release">
    <img alt="semantic-release" src="https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg">
  </a>

  <!-- <a href="https://app.netlify.com/sites/gobarber-react-web/deploys">
    <img alt="Netlify Status" src="https://api.netlify.com/api/v1/badges/dd225487-0a31-4b67-8d9c-8006280cce71/deploy-status">
  </a> -->
</p>

## [🔝](#top) License :closed_lock_with_key:

Copyright © 2021 GoBarber, [MIT](https://github.com/caiohenrique-developer/react-native-deploy/blob/master/LICENSE) .
###### _This project is under the <sup>MIT</sup> license. See the license for more information._

---

<blockquote align="center">“Always running in search of the goals!” <br> Done with ♥ by myself 👇 <a href="#-contact-me-phone">Get in touch!</a></blockquote>

## [🔝](#top) Contact Me :phone:

<p align="left">
  <img align="left" alt="Profile Avatar" src="./src/assets/professional.png" width="80" />

  <br>

  <a href="https://www.linkedin.com/in/caio-henrique-024627171">
    <img align="center" alt="LinkedIn" src="https://img.shields.io/badge/Caio%20Henrique-0077B5?logo=linkedin&logoColor=white&style=flat-square" />
  </a>
  <a href="mailto:caiohenrique.developer@gmail.com">
    <img align="center" alt="Gmail" src="https://img.shields.io/badge/caiohenrique.developer@gmail.com-D14836?logo=gmail&logoColor=white&style=flat-square" />
  </a>
  <a href="https://api.whatsapp.com/send?phone=5511943902438&text=Fala%20Caio,%20como%20vai?">
    <img align="center" alt="Whatsapp" src="https://img.shields.io/badge/(11)%2094390%202438-25D366?style=social&logo=whatsapp&logoColor=black" />
  </a>
</p>

[nodejs]: https://nodejs.org/
[yarn]: https://yarnpkg.com/
[vc]: https://code.visualstudio.com/
[vceditconfig]: https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig
[vceslint]: https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint
[vcprettier]: https://prettier.io/
