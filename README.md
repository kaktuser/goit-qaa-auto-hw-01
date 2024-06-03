# goit-qaa-auto-hw-01

bash-5.2$ npm init --yes
Wrote to /home/piotr/Dokumenty/GitHub/goit-qaa-auto-hw-01/package.json:

{
"name": "goit-qaa-auto-hw-01",
"version": "1.0.0",
"description": "",
"main": "index.js",
"scripts": {
"test": "echo \"Error: no test specified\" && exit 1"
},
"keywords": [],
"author": "",
"license": "ISC"
}

bash-5.2$ npm install cypress --save-dev

added 173 packages, and audited 174 packages in 32s

39 packages are looking for funding
run `npm fund` for details

found 0 vulnerabilities
bash-5.2$ npx cypress open
Gtk-Message: 23:04:59.041: Failed to load module "canberra-gtk-module"
Gtk-Message: 23:04:59.041: Failed to load module "pk-gtk-module"
Gtk-Message: 23:04:59.042: Failed to load module "canberra-gtk-module"
Gtk-Message: 23:04:59.042: Failed to load module "pk-gtk-module"

DevTools listening on ws://127.0.0.1:40309/devtools/browser/a5c79726-af6b-4ce9-a3f1-1cedb4e1fb6e
GET /**/ 200 19.607 ms - -
GET /**/assets/index-3fd9e8ed.css 200 16.058 ms - -
GET /**/assets/polyfills-3023ae52.js 200 45.262 ms - -
GET /**/assets/index-3fe21bb9.js 200 17.355 ms - -
GET /**cypress/runner/cypress_runner.css 200 2.489 ms - -
GET /**/assets/Specs-4115352f.js 200 3.165 ms - 523
GET /**/assets/route-block-c0a8bdd8.js 200 3.084 ms - 45
GET /**/assets/TrackedBanner.vue_vue_type_script_setup_true_lang-5951d338.js 200 3.117 ms - -
GET /**/assets/InlineCodeFragment-63f519c9.css 200 5.688 ms - 310
GET /**/assets/Index-f90bad12.css 200 4.806 ms - -
GET /**/assets/InlineCodeFragment.vue_vue_type_script_setup_true_lang-2ebf3d7b.js 200 2.991 ms - -
GET /**/assets/box-open_x48-5f9fb7b5.js 200 6.329 ms - -
GET /**/assets/Index-61c9d6a8.js 200 3.211 ms - -
GET /**/assets/SpecPatterns.vue_vue_type_script_setup_true_lang-27b38053.js 200 13.195 ms - -
GET /**/assets/graphql-5752d761.js 200 25.136 ms - 535
GET /**/assets/SpecNameDisplay.vue_vue_type_script_setup_true_lang-9e6cef72.js 200 25.049 ms - -
GET /**/assets/PromoHeader.vue_vue_type_script_setup_true_lang-1bb58a00.js 200 40.068 ms - -
GET /**/assets/settings_x16-a9b74cd2.js 200 18.125 ms - -
GET /**/assets/cypress_s-29af549a.png 200 10.892 ms - 4425
GET /**/assets/electron-fb07f5cc.svg 200 1.563 ms - -
GET /**cypress/runner/cypress_runner.js 200 2.829 ms - -
GET /**/fonts/FiraCode-VF.woff2 404 38.603 ms - -
GET /**/assets/onigasm-b63d2d2d.wasm 200 3.753 ms - -
GET /**/assets/Switch.vue_vue_type_script_setup_true_lang-aa15826b.js 200 7.927 ms - -
GET /**/assets/refresh_x16-963a23f0.js 200 6.966 ms - -
GET /**/assets/Runner-d26b5796.css 200 6.226 ms - -
GET /**/assets/Runner-888097d3.js 200 9.498 ms - -
GET /**cypress/iframes/cypress%2Fe2e%2Fspec.cy.js?browserFamily=chromium 200 4.903 ms - -
GET /**cypress/tests?p=cypress/e2e/spec.cy.js 200 980.042 ms - 994
GET /**cypress/tests?p=cypress/support/e2e.js 200 995.298 ms - -
GET /**/ 200 2.125 ms - -
GET /**/assets/index-3fd9e8ed.css 200 4.782 ms - -
GET /**/assets/polyfills-3023ae52.js 200 1.568 ms - -
GET /**/assets/index-3fe21bb9.js 200 3.647 ms - -
GET /**cypress/runner/cypress_runner.css 200 0.980 ms - -
GET /**/assets/Specs-4115352f.js 200 3.849 ms - 523
GET /**/assets/route-block-c0a8bdd8.js 200 3.881 ms - 45
GET /**/assets/InlineCodeFragment-63f519c9.css 200 6.464 ms - 310
GET /**/assets/Runner-d26b5796.css 200 6.064 ms - -
GET /**/assets/box-open_x48-5f9fb7b5.js 200 3.361 ms - -
GET /**/assets/InlineCodeFragment.vue_vue_type_script_setup_true_lang-2ebf3d7b.js 200 4.914 ms - -
GET /**/assets/SpecPatterns.vue_vue_type_script_setup_true_lang-27b38053.js 200 24.940 ms - -
GET /**/assets/Switch.vue_vue_type_script_setup_true_lang-aa15826b.js 200 12.963 ms - -
GET /**/assets/refresh_x16-963a23f0.js 200 3.023 ms - -
GET /**/assets/Runner-888097d3.js 200 5.386 ms - -
GET /**/assets/graphql-5752d761.js 200 5.190 ms - 535
GET /**/assets/cypress_s-29af549a.png 200 1.293 ms - 4425
GET /**cypress/runner/cypress_runner.js 200 1.024 ms - -
GET /**/assets/electron-fb07f5cc.svg 200 0.626 ms - -
GET /**cypress/iframes/cypress%2Fe2e%2Fspec.cy.js?browserFamily=chromium 200 1.126 ms - -
GET /**cypress/tests?p=cypress/e2e/spec.cy.js 200 1.624 ms - 994
GET /**cypress/tests?p=cypress/support/e2e.js 200 2.207 ms - -
GET / 200 14.458 ms - -
GET /assets/css/vendor/fira.css 200 209.789 ms - -
GET /assets/css/vendor/bootstrap.min.3cdc65ed.css 200 173.649 ms - -
GET /assets/css/styles.188b2993.css 200 275.363 ms - -
GET /assets/js/vendor/highlight.pack.4cbe7783.js 200 206.173 ms - -
GET /assets/js/vendor/bootstrap.min.c5b5b2fa.js 200 211.466 ms - -
GET /assets/js/vendor/jquery-1.12.0.min.cbb11b58.js 200 219.850 ms - -
GET /assets/js/scripts.65b859b5.js 200 176.313 ms - -
GET /assets/fonts/woff/FiraSans-Regular.woff 200 73.225 ms - -
GET /assets/fonts/woff/FiraSans-Medium.woff 200 102.716 ms - -
