# CSS PAGED MEDIA

  Mobile-first classes for css-paged-media.
  Set the desired css-paged-media on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
```
npm install --save-dev css-paged-media
```
or download the css on github and include in your project.

## File Size


## The Code
```
 * print styles.
 *
 */

.page-ba-auto {   page-break-after: auto; }
.page-ba-always { page-break-after: always; }
.page-ba-avoid {  page-break-after: avoid; }
.page-ba-l {      page-break-after: left; }
.page-ba-r {      page-break-after: right; }
.page-ba-i {      page-break-after: inherit; }

.page-bb-auto {   page-break-before: auto; }
.page-bb-always { page-break-before: always; }
.page-bb-avoid {  page-break-before: avoid; }
.page-bb-l {      page-break-before: left; }
.page-bb-r {      page-break-before: right; }
.page-bb-i {      page-break-before: inherit; }

.page-bi-auto {   page-break-inside: auto; }
.page-bi-avoid {  page-break-inside: avoid; }
.page-bi-i {      page-break-inside: inherit; }

```

## Author

[http://mrmrs.cc](http://mrmrs.cc - Entire internet gateway to all things mrmrs)
[http://mrmrs.io](http://mrmrs.io - Open source projects)

## License

The MIT License (MIT)

Copyright (c) 2014 @mrmrs

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

