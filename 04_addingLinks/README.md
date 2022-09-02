## Syntaxes

### Add a link to another page
To add link in an HTML file, we use the anchor tag with the **href** attribute.
```html
<a href="https://developer.mozilla.org/">MDN</a>
```
Try it: <a href="https://developer.mozilla.org/">MDN</a>

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
Example on this page:
<nav>
  <ul>
    <li><a href="https://github.com/Lamy237/html-course/main#add-a-link-to-another-page">First title</a></li>
    <li><a href="https://github.com/Lamy237/html-course/main#add-a-link-to-the-current-page">Second title</a></li>
  </ul>
</nav>

### Back to top
We can add a link to bring us back to the top of the page by just passing a hashtag to the **href** attribute.
```html
<a href="#">Back to Top</a>
```
Try it: <a href="#">Back to Top</a>
