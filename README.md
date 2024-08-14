# CSS Override

## Setup files

- Create a public repo
- Create a file called `override.css`
- Create a file called `index.html`

## Setup Pages

- Host the files. If you're using github, we recommend github pages.
- https://pages.github.com/

## Override CSS

- Visit your dex: https://demo.0sum.io/
- Right click > `Inspect Element`
- Select the DOM you want to edit and make changes.
- Add the changes to `override.css`

## Example

### Inspect Element

![](https://github.com/user-attachments/assets/d845ef77-ca87-4ccd-a5d4-a0d4cad1eb39)

### override.css
```css
[class*="App__BodyWrapper"] {
  background-color: red !important;
}
```

### Result

![](https://github.com/user-attachments/assets/7afbd79c-ee49-42c3-bc9e-286e017ec124)
