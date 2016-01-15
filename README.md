# css-paged-media 0.0.6

Css module of single purpose classes for paged media

#### Stats

258 | 15 | 15
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-paged-media
```

#### With Git

```
git clone https://github.com/tachyons-css/css-paged-media
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-paged-media";
```

Then process the CSS using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons-cli path/to/css-file.css > dist/t.css
```

#### Using the CSS

The built CSS is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-paged-media">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*
   PAGED MEDIA
*/
/*
 * I don't think we need screen-width based media queries for these
 * print styles.
 *
 */
.page-ba-auto { page-break-after: auto; }
.page-ba-always { page-break-after: always; }
.page-ba-avoid { page-break-after: avoid; }
.page-ba-l { page-break-after: left; }
.page-ba-r { page-break-after: right; }
.page-ba-i { page-break-after: inherit; }
.page-bb-auto { page-break-before: auto; }
.page-bb-always { page-break-before: always; }
.page-bb-avoid { page-break-before: avoid; }
.page-bb-l { page-break-before: left; }
.page-bb-r { page-break-before: right; }
.page-bb-i { page-break-before: inherit; }
.page-bi-auto { page-break-inside: auto; }
.page-bi-avoid { page-break-inside: avoid; }
.page-bi-i { page-break-inside: inherit; }
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## Authors

* [mrmrs](http://mrmrs.io)
* [johno](http://johnotander.com)

## License

MIT

