## Getting Started

You'll need to install Node.js and Gulp before using.

1. Make sure you have node.js (https://nodejs.org/en/) installed
2. Type `npm install` in terminal/console in the source folder where `package.json` is located
3. You will find all the branding colors inside `assets/scss/_variables.scss`. You can change them with a `HEX` value.
4. Run in terminal `gulp compile:scss` for a single compilation or `gulp watch` for continous compilation of the changes that you make in `*.scss` files. This command should be run in the same folder where `gulpfile.js` and `package.json` are located
5. Run in terminal `gulp` for opening.

now-ui-kit/
  ├── README.md
  ├── assets/
  │   ├── css/
  │   │   ├── bootstrap.min.css
  │   │   ├── demo.css
  │   │   └── now-ui-kit.css
  │   ├── fonts/
  │   │   ├── nucleo-license.md
  │   │   ├── nucleo-outline.eot
  │   │   ├── nucleo-outline.ttf
  │   │   ├── nucleo-outline.woff
  │   │   └── nucleo-outline.woff2
  │   ├── img/
  │   ├── js/
  │   │   ├── core/
  │   │   │   ├── bootstrap.min.js
  │   │   │   ├── jquery.3.2.1.min.js
  │   │   │   └── popper.min.js
  │   │   ├── now-ui-kit.js
  │   │   └── plugins/
  │   │       ├── bootstrap-datetimepicker.min.js
  │   │       ├── bootstrap-selectpicker.js
  │   │       ├── bootstrap-switch.js
  │   │       ├── bootstrap-tagsinput.js
  │   │       ├── jasny-bootstrap.min.js
  │   │       ├── moment.min.js
  │   │       ├── nouislider.min.js
  │   │       └── presentation-page
  │   │           └── rellax.min.js
  │   └── scss
  │       ├── demo.scss
  │       ├── now-ui-kit/
  │       └── now-ui-kit.scss
  ├── gulpfile.js
  ├── index.html
  ├── nucleo-icons.html
  ├── package.json
```
