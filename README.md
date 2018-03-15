# mix-starter
A laravel-mix-based starter for prototyping

will compile SASS, supports vue single-file components

## Usage
Is pretty simple - `package.json` has a set of scripts from compiling everything to `dist/`, including `npm run serve` that will launch a webpack dev server on port `8080` that you can access.

## Being more specific
Since this starter template is for my uses I've included a number of libraries by default

- vue
- bootstrap
- bootstrap-vue
- axios

Use or don't as you please

The scripts currently available

- `serve` - spins up a webpack-dev-server instance on `8080` so you can test things out for real
- `hot` - alias for `serve`
- `prod` - includes production level minification of css/sass/scss/js
- `dev` - one off compilation without the minification
- `watch` - listen for changes and recompile when they happen
