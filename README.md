# cryowire Artwork

Official logos and brand assets for [cryowire](https://github.com/cryowire).

## Logo

Icon mark only.

![logo](logo/logo.png)

## Logo Type

Logo with "cryowire" text.

![logo-type](logo-type/logo-type.png)

## Favicon

Favicons generated from the logo for web use.

| File | Size | Usage |
|---|---|---|
| `favicon.ico` | 16x16, 32x32, 48x48 | Browser tab (multi-size ICO) |
| `favicon-16x16.png` | 16x16 | Small PNG |
| `favicon-32x32.png` | 32x32 | Standard PNG |
| `favicon-48x48.png` | 48x48 | Medium PNG |
| `apple-touch-icon.png` | 180x180 | iOS home screen |
| `android-chrome-192x192.png` | 192x192 | Android Chrome |
| `android-chrome-512x512.png` | 512x512 | Android Chrome (high-res) |

### HTML Usage

```html
<link rel="icon" type="image/x-icon" href="/favicon.ico">
<link rel="icon" type="image/png" sizes="32x32" href="/favicon-32x32.png">
<link rel="icon" type="image/png" sizes="16x16" href="/favicon-16x16.png">
<link rel="apple-touch-icon" sizes="180x180" href="/apple-touch-icon.png">
```

## Directory Structure

```
artwork/
├── favicon/
│   ├── android-chrome-192x192.png
│   ├── android-chrome-512x512.png
│   ├── apple-touch-icon.png
│   ├── favicon-16x16.png
│   ├── favicon-32x32.png
│   ├── favicon-48x48.png
│   └── favicon.ico
├── logo/
│   └── logo.png
├── logo-type/
│   └── logo-type.png
└── README.md
```

## License

Licensed under the Apache License, Version 2.0. See [LICENSE](LICENSE) for details.
