node: 24.6.0
npm: 10.9.2
npm init
sass: npm install --save-dev sass
bootstrap: npm install bootstrap
fontawesome: npm i @fortawesome/fontawesome-free  (https://www.npmjs.com/package/@fortawesome/fontawesome-free)

prefixer: npm install postcss postcss-cli autoprefixer (https://www.npmjs.com/package/autoprefixer)

run: npm run compile:sass

Source maps: 
Source maps are files that tell browsers or other tools that consume CSS how that CSS corresponds to the Sass files from which it was generated.
They make it possible to see and even edit your Sass files in browsers.

### Variables
node_modules -> bootstrap -> scss -> _variables.scss

bootstrap-accordian-icon: plus-circle
<svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-plus-circle" viewBox="0 0 16 16">
  <path d="M8 15A7 7 0 1 1 8 1a7 7 0 0 1 0 14m0 1A8 8 0 1 0 8 0a8 8 0 0 0 0 16"/>
  <path d="M8 4a.5.5 0 0 1 .5.5v3h3a.5.5 0 0 1 0 1h-3v3a.5.5 0 0 1-1 0v-3h-3a.5.5 0 0 1 0-1h3v-3A.5.5 0 0 1 8 4"/>
</svg>

bootstrap-accordian-icon: dash-circle
<svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-dash-circle" viewBox="0 0 16 16">
  <path d="M8 15A7 7 0 1 1 8 1a7 7 0 0 1 0 14m0 1A8 8 0 1 0 8 0a8 8 0 0 0 0 16"/>
  <path d="M4 8a.5.5 0 0 1 .5-.5h7a.5.5 0 0 1 0 1h-7A.5.5 0 0 1 4 8"/>
</svg>