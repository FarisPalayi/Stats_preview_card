# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62).

## Screenshot

<br>

![screenshot of the stats preview card component](./images/project-screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

### Built with

- HTML
- CSS

### Responsive to :

- Mobile
- Desktop
- Tablet
- 4K (Not sure though, if you have a 4k display please let me know)

## Supported Browsers

- Chrome
- Firefox
- Edge
- Opera
- IE11
- If you have Safari browser, please let me know if it works on it or not.

### What I learned

I learned some new handy CSS selectors.

For example, instead writing this:

```css
.selector {
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
}
```

I learned that you can write it in one line like this:

```css
selector {
  inset: 0;
}
```

And I also learned the `background-blend-mode` property. This comes in handy when you want to combine `background-image` and `background-color` or to combine multiple background-images.

```css
.selector {
  background-blend-mode: multiply;
}
```

It was a little bit hard to make it responsive. However, he real challenge was to make it compatible with internet explorer (version 11). So, while doing this I learned that:

IE doesn't support:

```
css variables ( custom properties)
functions like min(),max(), and clamp()
% values to height when using width's unit as a % value
background shorthand property
full support of css grid
```

<br><br>

### Continued development

I realized that there are a lot of things I need to learn when it comes to cross-browser compatibility, but I also realized that I can solve these problems and move forward.

### Useful resources

- [caniuse](https://www.caniuse.com)
- [MDN Web docs](https://developer.mozilla.org/en-US/)
- [CSS Tricks](https://css-tricks.com/)
- [W3schools](w3schools.com/)
- [Stack overflow](<[w3schools.com/](https://stackoverflow.com/)>)

## Author

- Github - [Faris P](https://www.github.com/FarisPalayi)
- Frontend Mentor - [@FarisPalayi](https://www.frontendmentor.io/profile/FarisPalayi)
- Twitter - [@farispalayi](https://www.twitter.com/farispalayi)
- Email - [farispalayi@gmail.com](mailto:farispalayi@gmail.com)

<br>
<sub>*feel free to correct any typos or grammatical errors in this file.</sub>
