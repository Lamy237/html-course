# Semantic Elements

A semantic element clearly describes its meaning to both the browser and the developer.

Many web sites contain HTML code like the following to indicate **navigation**, **header**, and **footer**.
```html
<div class="header">
  <div id="nav"></div>
</div>
<div id="footer"></div>
```

In HTML there are some semantic elements that can be used to define different parts of a web page.

## Examples of semantic elements

A semantic element clearly defines its content. Some examples include:
- [`<header>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/header)
- [`<nav>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/nav)
- [`<main>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/main)
- [`<footer>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/footer)
- [`<form>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/form)
- [`<table>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/table)
- [`<article>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/article)

```html
<header>
  <!--  header content here  -->
  <nav>
    <!--  nav content here  -->
  </nav>
</header>

<main>
  <!--  main content here  -->
</main>

<footer>
  <!--  footer content here  -->
</footer>
```

## Examples of non-semantic elements

These are elements that tell nothing about their content.

| Element | Description |
|---------|-------------|
| [`<div>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/div) | The generic container for flow content. It has no effect on the content or layout until styled in some way using CSS. |
| [`<span>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/span) | A generic inline container for phrasing content, which does not inherently represent anything.  |

# Important notes

- There can be more then one `header` and `footer`, but there can only be one `main` element.

- There can be more than one `nav` element per page as well. We might have a one in the `footer` for example, as footers often have links to other areas of the website.

- In case you have more than one `nav` element on your page, it's important to label them with the attirbute `aria-label`.

# 📚 References

- 🔗 [MDN Web Glossary: Semantics](https://developer.mozilla.org/en-US/docs/Glossary/Semantics)
- 🔗 [w3Schools: Semantic HTML](https://www.w3schools.com/html/html5_semantic_elements.asp)
- 🔗 [MDN: Document and Website Structure](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Document_and_website_structure)
