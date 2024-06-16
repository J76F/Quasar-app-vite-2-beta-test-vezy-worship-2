PS C:\Users\Jeroen Faber> cd .\Documents\VS-Code\
PS C:\Users\Jeroen Faber\Documents\VS-Code> npm install -g @quasar/cli 

changed 227 packages in 17s        

78 packages are looking for funding
  run `npm fund` for details       
PS C:\Users\Jeroen Faber\Documents\VS-Code> npm init quasar@latest    


 .d88888b.
d88P" "Y88b
888     888
888     888 888  888  8888b.  .d8888b   8888b.  888d888
888     888 888  888     "88b 88K          "88b 888P"
888 Y8b 888 888  888 .d888888 "Y8888b. .d888888 888
Y88b.Y8b88P Y88b 888 888  888      X88 888  888 888
 "Y888888"   "Y88888 "Y888888  88888P' "Y888888 888
       Y8b

√ What would you like to build? » App with Quasar CLI, let's go!
√ Project folder: ... vezy-worship-2
√ Pick Quasar version: » Quasar v2 (Vue 3 | latest and greatest)
√ Pick script type: » Javascript
√ Pick Quasar App CLI variant: » Quasar App CLI with Vite 5 (BETA | next major version - v2)
√ Package name: ... vezy-worship
√ Project product name: (must start with letter if building mobile apps) ... VezyWorship
√ Project description: ... Presentatiesoftware voor beamer én livestream
√ Author: ... Jan-Paul Kleemans <jpkleemans@gmail.com> & Jeroen Faber
√ Pick a Vue component style: » Options API
√ Pick your CSS preprocessor: » Sass with SCSS syntax
√ Check the features needed for your project: » Linting (vite-plugin-checker + ESLint), State Management (Pinia), axios       
√ Pick an ESLint preset: » Standard

 Quasar • Generating files...      

 - index.html       
 - postcss.config.js
 - quasar.config.js 
 - README.md    
 - .editorconfig
 - .gitignore
 - .npmrc
 - jsconfig.json
 - package.json
 - public/favicon.ico
 - src/App.vue
 - .vscode/extensions.json
 - .vscode/settings.json
 - public/icons/favicon-128x128.png
 - public/icons/favicon-16x16.png
 - public/icons/favicon-32x32.png
 - public/icons/favicon-96x96.png
 - src/assets/quasar-logo-vertical.svg
 - src/boot/.gitkeep
 - src/components/EssentialLink.vue
 - src/layouts/MainLayout.vue
 - src/pages/ErrorNotFound.vue
 - src/pages/IndexPage.vue
 - src/router/index.js
 - src/router/routes.js
 - src/css/app.scss
 - src/css/quasar.variables.scss
 - src/boot/axios.js
 - .eslintignore
 - .eslintrc.cjs
 - src/stores/example-store.js
 - src/stores/index.js
 - src/stores/store-flag.d.ts

 Quasar •  SUCCESS  • The project has been scaffolded

√ Install project dependencies? (recommended) » No, I will handle that myself

To get started:

  cd vezy-worship-2
  yarn #or: npm install
  yarn lint --fix # or: npm run lint -- --fix
  quasar dev # or: yarn quasar dev # or: npx quasar dev

Documentation can be found at: https://v2.quasar.dev

Quasar is relying on donations to evolve. We'd be very grateful if you can
read our manifest on "Why donations are important": https://v2.quasar.dev/why-donate
Donation campaign: https://donate.quasar.dev
Any amount is very welcome.
If invoices are required, please first contact Razvan Stoenescu.

Please give us a star on Github if you appreciate our work:
  https://github.com/quasarframework/quasar

Enjoy! - Quasar Team

PS C:\Users\Jeroen Faber\Documents\VS-Code>   

-----------------
open vs-code in de map: ...\vezy-worship-2
Update package.json naar nieuwste versies
 - behalve eslint(8.57.0) & eslint-plugin-n (16.6.2) --> update gaf problemen in versie 1.9.7 van vezy
npm install 
-----------------
PS C:\Users\Jeroen Faber\Documents\VS-Code\vezy-worship-2> npm install
npm WARN deprecated inflight@1.0.6: This module is not supported, and leaks 
memory. Do not use it. Check out lru-cache if you want a good and tested way to coalesce async requests by a key value, which is much more comprehensive and powerful.
npm WARN deprecated @humanwhocodes/config-array@0.11.14: Use @eslint/config-array instead
npm WARN deprecated rimraf@3.0.2: Rimraf versions prior to v4 are no longer supported
npm WARN deprecated glob@7.2.3: Glob versions prior to v9 are no longer supported
npm WARN deprecated @humanwhocodes/object-schema@2.0.3: Use @eslint/object-schema instead

added 560 packages, and audited 561 packages in 57s

165 packages are looking for funding
  run `npm fund` for details

found 0 vulnerabilities

PS C:\Users\Jeroen Faber\Documents\VS-Code\vezy-worship-2> npm run lint -- --fix

> vezy-worship@0.0.1 lint
> eslint --ext .js,.vue ./ --fix


C:\Users\Jeroen Faber\Documents\VS-Code\vezy-worship-2\src\layouts\MainLayout.vue
  49:27  error  'ref' is defined but never used  no-unused-vars

✖ 1 problem (1 error, 0 warnings)

PS C:\Users\Jeroen Faber\Documents\VS-Code\vezy-worship-2>
----------
--> verwijder ref import uit \src\layouts\MainLayout.vue
--> zet versie naar 2.0.0-beta
----------

PS C:\Users\Jeroen Faber\Documents\VS-Code\vezy-worship-2> npm run lint -- --fix

> vezy-worship@0.0.1 lint
> eslint --ext .js,.vue ./ --fix

PS C:\Users\Jeroen Faber\Documents\VS-Code\vezy-worship-2> npm install

up to date, audited 561 packages in 2s

165 packages are looking for funding
  run `npm fund` for details

found 0 vulnerabilities
PS C:\Users\Jeroen Faber\Documents\VS-Code\vezy-worship-2>
PS C:\Users\Jeroen Faber\Documents\VS-Code\vezy-worship-2> npm run dev

> vezy-worship@2.0.0-beta dev
> quasar dev


 .d88888b.
d88P" "Y88b
888     888
888     888 888  888  8888b.  .d8888b   8888b.  888d888
888     888 888  888     "88b 88K          "88b 888P"
888 Y8b 888 888  888 .d888888 "Y8888b. .d888888 888
 "Y888888"   "Y88888 "Y888888  88888P' "Y888888 888

 App • Using quasar.config.js in "esm" format

 » Reported at............ 16-6-2024 22:35:20
 » App dir................ C:\Users\Jeroen Faber\Documents\VS-Code\vezy-worship-2
 » App URL................ http://192.168.178.145:9000/
                           http://localhost:9000/
 » Dev mode............... spa
 » Pkg quasar............. v2.16.4
 » Pkg @quasar/app-vite... v2.0.0-beta.14
 » Browser target......... es2022|firefox115|chrome115|safari14

 App • Opening default browser at http://localhost:9000/

[ESLint] Found 0 error and 0 warning
Terminate batch job (Y/N)? y

---
maak in github https://github.com/J76F/vezy-worship-2 aan.
Koppel map.
---
PS C:\Users\Jeroen Faber\Documents\VS-Code\vezy-worship-2> git init
PS C:\Users\Jeroen Faber\Documents\VS-Code\vezy-worship-2> git add -A
PS C:\Users\Jeroen Faber\Documents\VS-Code\vezy-worship-2> git commit -m "Init @quasar/app-vite v2 (beta) 14"
PS C:\Users\Jeroen Faber\Documents\VS-Code\vezy-worship-2> git branch -M main
PS C:\Users\Jeroen Faber\Documents\VS-Code\vezy-worship-2> git remote add origin https://github.com/J76F/vezy-worship-2.git 
PS C:\Users\Jeroen Faber\Documents\VS-Code\vezy-worship-2> git push -u origin main
PS C:\Users\Jeroen Faber\Documents\VS-Code\vezy-worship-2> 