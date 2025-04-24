> [!CAUTION]
> This is a fork of [filiphric/slidev-theme-excali-slide](https://github.com/filiphric/slidev-theme-excali-slide) intended for personal usage.
> The primary difference is that this theme was modified to use excalidraw's new [excalifont](https://plus.excalidraw.com/excalifont)
> If you are looking for a theme to use with slidev please check the original repo first.

# slidev-theme-excalifont

A [Excalidraw](https://excalidraw.com/)-like theme for [Slidev](https://github.com/slidevjs/slidev).

- [ ] TODO: add light mode screenshot

Theme works in dark mode too. In this case, the highlight color have the opacity set to 0.9.

- [ ] TODO: add dark mode screenshot

Theme comes with animated heading highlights. You can customize their colors by setting up following properties:

<pre><code>---
themeConfig:
  primary-highlight: '#F3EFF5'
  secondary-highlight: '#161C2C'
  marker-animation: disabled; // optional
---</code></pre>

## Install

Add the following frontmatter to your `slides.md`. Start Slidev then it will prompt you to install the theme automatically.

<pre><code>---
theme: <b>excalifont</b>
---</code></pre>

Learn more about [how to use a theme](https://sli.dev/guide/theme-addon#use-theme).

## Contributing

- `npm install`
- `npm run dev` to start theme preview of `example.md`
- Edit the `example.md` and style to see the changes
- `npm run export` to generate the preview PDF
- `npm run screenshot` to generate the preview PNG
