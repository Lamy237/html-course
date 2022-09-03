## Syntaxes

### Add a link to another page
To add link in an HTML file, we use the anchor tag with the **href** attribute.
```html
<a href="https://developer.mozilla.org/">MDN</a>
```

### Open link in a new tab
To open a link in a new tab, set the attribute **target** to **_blank**.
```html
<p>
  Open <a href="https://www.google.com/" target="_blank">Google</a> in a new tab.
</p>
```

### Add a link to the current page
We can also add links to the current page by adding the **id** attributes to targeted area on the page as well as a **nav** element.
```html
<nav>
  <ul>
    <li><a href="#earth">Earth</li>
    <li><a href="#mars">Mars</li>
  </ul>
</nav>

<section id="earth">
  <p>Home the humans</p>
</section>
<section id="mars">
  <p>Empty planet, no human life so far</p>
</section>
```

### Back to top
We can add a link to bring us back to the top of the page by just passing a hashtag to the **href** attribute.
```html
<a href="#">Back to Top</a>
```

### Back to home
To go back to the home page, pass a slash to the **href** attribute.
```html
<a href="/">Back to home</a>
```

### Download from a link
To download an item (image, file, ...etc) on a click, add the **download** attribute in the anchor tag.
```html
<p>
  Download an <a href="html5.png" download>HTML favicon</a>.
</p>
```

### Email link (not recomended)
```html
<p>
  Contact me at <a href="mailto:random@email.com">my email address</a>
</p>
```

### Phone number link
```html
<p>
  Dial <a href="tel:+1234567890">my phone number</a>
</p>
```




