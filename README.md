# css-paged-media

Functional CSS for paged-media

## Filesize

| File | Size |
|------|------|
| `dist/paged-media.css` | 687 bytes |
| `dist/paged-media.min.css` | 553 bytes (158 Gzipped) |

## Install

```sh
npm install css-paged-media
```

## Usage

### Import

```css
@import "css-paged-media";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-paged-media/dist/paged-media.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-paged-media/dist/paged-media.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.page-ba-auto` | `page-break-after: auto;` |
| `.page-ba-always` | `page-break-after: always;` |
| `.page-ba-avoid` | `page-break-after: avoid;` |
| `.page-ba-l` | `page-break-after: left;` |
| `.page-ba-r` | `page-break-after: right;` |
| `.page-ba-i` | `page-break-after: inherit;` |
| `.page-bb-auto` | `page-break-before: auto;` |
| `.page-bb-always` | `page-break-before: always;` |
| `.page-bb-avoid` | `page-break-before: avoid;` |
| `.page-bb-l` | `page-break-before: left;` |
| `.page-bb-r` | `page-break-before: right;` |
| `.page-bb-i` | `page-break-before: inherit;` |
| `.page-bi-auto` | `page-break-inside: auto;` |
| `.page-bi-avoid` | `page-break-inside: avoid;` |
| `.page-bi-i` | `page-break-inside: inherit;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.page-ba-auto-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/paged-media.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/paged-media.css` — formatted
- `dist/paged-media.min.css` — minified

## License

MIT
