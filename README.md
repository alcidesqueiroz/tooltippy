# tooltippy [![Build status](https://travis-ci.com/alcidesqueiroz/tooltippy.svg?branch=master)](https://travis-ci.com/alcidesqueiroz/tooltippy)

> 💬 Graceful CSS-only tooltips in under 1kb gzipped.

![Tooltippy is sexy!](https://gist.githubusercontent.com/alcidesqueiroz/c3d6c6edc559194bc37a2c464a21768d/raw/8d8b01f62703f8cb7442e369ef805965c1efe77e/tooltippy.png)

## Install

With npm:
```
$ npm install tooltippy
```

With Yarn:

```
$ yarn add tooltippy
```

## Usage

1. Pick one of the available themes (you can see animated previews below);
2. Import your theme's stylesheet (from inside the `/dist` folder). Naturally, the recommended format for production is the minified one, but expanded and debug versions are available for each theme too;
3. In your target element, set the value of the `data-tooltippy` attribute to the text you want to show;
4. Add the `.tooltippy` class to your target element;
5. Define the position of your tooltip by using one of the existing direction classes (`.tooltippy--top`, `.tooltippy--left`, `.tooltippy--bottom` and `.tooltippy--right`);
6. **Optional step**: If you want, you can import the suggested font-face for the theme you have chosen. All theme stylesheets have font-stacks with similar web-safe font-families as fallback.


```html
<div class="tooltippy tooltippy--top" data-tooltippy="Hodor... Hodor?? Hodor!">
  <img src="hodor.jpg" />
</div>
```

- **IMPORTANT NOTICE 1**: In order to behave correctly, the tooltip target element *MUST* have its `position` set to `relative`, `absolute` or `fixed`.
- **IMPORTANT NOTICE 2**: [Replaced elements](https://stackoverflow.com/a/6949190) (like `img` or `input`) can't be used as target.

## Themes

### Hipster

- **Stylesheet:** `dist/tooltippy--hipster.min.css`
- **Suggested font-face:** [Raleway (weight 500)](https://fonts.googleapis.com/css?family=Raleway:500)

![Hipster theme](https://gist.githubusercontent.com/alcidesqueiroz/c3d6c6edc559194bc37a2c464a21768d/raw/278d1b8985497ff1fd58a7f6ecf3d102fadbd048/tooltippy--hipster.gif)

### Biz

- **Stylesheet:** `dist/tooltippy--biz.min.css`
- **Suggested font-face:** [Open Sans (weight 400)](https://fonts.googleapis.com/css?family=Open+Sans:400)

![Biz theme](https://gist.githubusercontent.com/alcidesqueiroz/c3d6c6edc559194bc37a2c464a21768d/raw/278d1b8985497ff1fd58a7f6ecf3d102fadbd048/tooltippy--biz.gif)

### Translucid

- **Stylesheet:** `dist/tooltippy--translucid.min.css`
- **Suggested font-face:** [Roboto Slab (weight 300)](https://fonts.googleapis.com/css?family=Roboto+Slab:300)

![Translucid theme](https://gist.githubusercontent.com/alcidesqueiroz/c3d6c6edc559194bc37a2c464a21768d/raw/278d1b8985497ff1fd58a7f6ecf3d102fadbd048/tooltippy--translucid.gif)

### High contrast

- **Stylesheet:** `dist/tooltippy--high-contrast.min.css`
- **Suggested font-face:** [Roboto (weight 500)](https://fonts.googleapis.com/css?family=Roboto:500)

![High contrast theme](https://gist.githubusercontent.com/alcidesqueiroz/c3d6c6edc559194bc37a2c464a21768d/raw/278d1b8985497ff1fd58a7f6ecf3d102fadbd048/tooltippy--high-contrast.gif)


## Author

Alcides Queiroz Aguiar

- Website: [www.alcidesqueiroz.com](https://www.alcidesqueiroz.com)
- Medium: [@alcidesqueiroz](https://medium.com/@alcidesqueiroz)
- Twitter: [alcidesqueiroz](https://twitter.com/alcidesqueiroz)
- Behance [alcidesqueiroz](https://behance.net/alcidesqueiroz)
- Stack Overflow: [http://is.gd/aqanso](http://stackoverflow.com/users/1295666/alcides-queiroz-aguiar)
- E-mail: alcidesqueiroz &lt;at&gt; gmail


## License

This code is free to use under the terms of the [MIT License](LICENSE.md).
