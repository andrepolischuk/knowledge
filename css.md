# CSS

## Sorting properties

```css
.selector {
  /* positioning */
  position: absolute;
  z-index: 10;
  top: 0;
  right: 0;

  /* display & box model */
  display: inline-block;
  overflow: hidden;
  box-sizing: border-box;
  width: 100px;
  height: 100px;
  padding: 10px;
  border: 10px solid #333;
  margin: 10px;

  /* color */
  background: #000;
  color: #fff;
  
  /* text */
  font-family: sans-serif;
  font-size: 16px;
  line-height: 1.4;
  text-align: right;

  /* other */
  cursor: pointer;
}
```

## Specificity

Selectors:

0. types, pseudo-elements: `h1`, `::after`
1. classes, attributes: `.class`, `[type="submit"]`
2. identifiers: `#id`

Nested example:

0. `h1 {...}`
1. `h1.title {...}`
2. `h1#title {...}`
3. `article h1 {...}`
4. `article.note h1 {...}`
5. `article#note h1 {...}`
6. `style="..."`

See also:

* [MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/Specificity)
* [Specificity calculator](https://specificity.keegan.st)
