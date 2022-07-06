# plusplusjakartasans

> Self-hosted webfont for Plus Jakarta Sans

### About

I stumbled upon this nice-looking font named [Plus Jakarta Sans](https://github.com/tokotype/PlusJakartaSans) (a sans-serif font developed by [Tokotype](http://www.tokotypefaces.com)), and I've been thinking of using it for my next project, however, there wasn't any available CDN links I could readily import. So I made this project to self-host the font files to provide a service similar to Google Fonts and also for me to easily add it in my future projects.

### Usage

using locally

```html
<link rel="stylesheet" href="path/to/plusjakartasans.css" />
```

via CDN using `<link>` tags

```html
<link
  rel="stylesheet"
  href="https://cdn.jsdelivr.net/npm/plusplusjakartasans@latest/plusjakartasans.css"
/>
```

```html
<link
  rel="stylesheet"
  href="https://unpkg.com/plusplusjakartasans/plusjakartasans.css"
/>
```

via CDN using `@import` in CSS

```css
@import url("https://cdn.jsdelivr.net/npm/plusplusjakartasans@latest/plusjakartasans.css");
html {
  font-family: "Plus Jakarta Sans", sans-serif;
}
```

```css
@import url("https://unpkg.com/plusplusjakartasans/plusjakartasans.css");
html {
  font-family: "Plus Jakarta Sans", sans-serif;
}
```

### Some useful links

- [Plus Jakarta Sans Repo](https://github.com/tokotype/PlusJakartaSans)

### License

- [Plus Jakarta Sans License](https://github.com/tokotype/PlusJakartaSans#license)
- [This Repo (MIT)](https://github.com/iamkentleom/plusplusjakartasans/blob/main/LICENSE)
