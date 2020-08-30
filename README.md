# Example: Angular with bootstrap-4-grid (only)

You can use the [Bootstrap 4 Grid System](https://getbootstrap.com/docs/4.0/layout/grid/) standalone (without using Bootstrap's component library). Bootstrap-4-grid can be used alongside [Angular Material](https://material.angular.io), Material Design components for Angular.

To add bootstrap-4-grid to an Angular project ...

```
npm install bootstrap-4-grid
```

Then add `./node_modules/bootstrap-4-grid/css/grid.css` to the styles section in *angular.json*.

###### angular.json
```js
"styles": [
  "src/styles.scss",
  "./node_modules/bootstrap-4-grid/css/grid.css"
],
```

See also ...

NPM package: [Bootstrap 4 Grid System (Flex)](https://www.npmjs.com/package/bootstrap-4-grid)


Bootstrap docs: [Bootstrap 4 Grid System Docs](https://getbootstrap.com/docs/4.0/layout/grid/)

## To run this example

With [Angular CLI](https://github.com/angular/angular-cli) version 9.1.9 installed ...

Clone or download this repo and run `npm install`

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. 

The app will automatically reload if you change any of the source files.

## Demo

[https://stevewitman.github.io/example-angular-with-bootstrap-4-grid-only/](https://stevewitman.github.io/example-angular-with-bootstrap-4-grid-only/)
