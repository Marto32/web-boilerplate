# Web Boilerplate

This is an html boilerplate template based on the following libraries / packages:

 * [Baseline](https://github.com/ajlkn/baseline)
 * [Skel 3](http://github.com/n33/skel)
 * [HTML5 Boilerplate](https://html5boilerplate.com/)

## File Structure

Here's a quick overview of how Baseline's files are organized:

File                        | Description
----------------------------|----------------------------------------------------------
`index.html`                | Main HTML
`static/`                   | Static Files
`  css/`                    | Stylesheets
`    main.css`              | Main stylesheet
`    font-awesome.min.css`  | Font Awesome's stylesheet
`  fonts/*`                 | Font Awesome's webfont files
`  images/*`                | Image files
`  js/`                     | Scripts
`    skel.min.js`           | Skel (JS framework)
`    main.js`               | Main JS (initializes Skel, off-canvas navigation, etc.)
`    vendor/*`              | Directory to store jquery and modernizr files
`  sass/`                   | Sass sources
`    main.scss`             | Main Sass stylesheet
`    base/*`                | Base styles
`    components/*`          | Reusable components (box, button, form, etc.)
`    layout/*`              | Primary layout components (header, footer, etc.)
`    libs/`                 | Helper libraries
`      _skel.scss`          | Skel.scss (Sass framework)
`      _vars.scss`          | Variables
`      _functions.scss`     | Functions
`      _mixins.scss`        | Mixins
`404.html`                  | Templated 404 page
`crossdomain.xml`           | Cross domain policy file [read this](http://www.adobe.com/devnet/articles/crossdomain_policy_file_spec.html)
`robots.txt`                | Instructions for web crawlers ([more info](http://www.robotstxt.org/robotstxt.html))

## Breakpoint Structure

Baseline is set up to use the following breakpoints (as noted [here](https://github.com/ajlkn/baseline#breakpoint-structure)):

Name*                     | Media Query
--------------------------|-----------------------
`xlarge`                  | `(max-width: 1680px)`
`large`                   | `(max-width: 1280px)`
`medium`                  | `(max-width: 980px)`
`small`                   | `(max-width: 736px)`
`xsmall`                  | `(max-width: 480px)`

## Notes

By default, this package uses a Python (and Django) based `.gitignore`. If you are using Wordpress, Jekyll or some other framework, you can rework the `.gitignore` file or use one of the templates [here](https://github.com/github/gitignore)

## Credits

- Font Awesome (http://fontawesome.io | (c) Dave Gandy | MIT license)
- classList (http://github.com/remy/polyfills | (c) @remy | rem.mit-license.org)
- Skel + Skel.scss (http://skel.io | (c) n33 | MIT license)
- HTML5 Boilerplate (https://html5boilerplate.com/ | (c) HTML5 Boilerplate | MIT license)
