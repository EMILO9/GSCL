[Documentation](https://emilo9.github.io/GSCL/) | [NPM]() | [Testing](https://stackblitz.com/edit/vue-psxzbw?file=src%2FApp.vue)

## How to set-up on your own machine:
```
git clone https://github.com/EMILO9/GSCL.git
cd gscl
npm install
code .
```
main.js
```
const { createApp } = require('vue');
import App from "./App.vue";

import GSCL from "gscl";
import 'gscl/dist/style.css'


createApp(App).use(GSCL).mount("#app");
```
