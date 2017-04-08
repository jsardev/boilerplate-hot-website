### Hot Website Boilerplate
This boilerplate was created to make an easy start for static websites development.
It comes with a configured webpack which handles live reloading of the changed website contents.

Webpack will automatically hot-reload changes in the `.scss` files (without browser reload)
and reload the browser on changes in the `.js` and `.html` files when running the `dev` mode (`npm run dev`).

#### How to use:

- Build production package: `npm run build`
- Development: `npm run dev`

The production package (`bundle.js` and `index.html`) will be placed in the `dist` folder.

#### To do list:

- Hot replacement of `.js` and `.html` files