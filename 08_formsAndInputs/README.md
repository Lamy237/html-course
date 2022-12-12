## Basics

### Create a form
A form can be created with the help of the **form** tag.
```html
<form action="https://httpbin.org/get" method="get">
  <!-- content here -->
</form>
```
**Note:** The attributes **action** and **method** may differ from the ones set in the above example.

### Add an input to the form
A form input can be created the following way :
```html
<label for="firstName">First Name:</label>
<input type="text" name="firstName" id="firstName">
```
Different input types include : **button, checkbox, color, date, datetime-local, email, file, hidden, image, month, number, password, radio, range, reset, search, submit, tel, text, time, url, week**.

## Important

- Only 1 input on the page can have the [`autofocus`](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/autofocus) attribute.
- The attribute [`selected`](https://www.w3schools.com/tags/att_option_selected.asp) is not supported on firefox. To fix this, you should add a `name` attribute to the form element.

## 📚 HTML Forms References: 
- 🔗 [MDN: Web Forms](https://developer.mozilla.org/en-US/docs/Learn/Forms)
- 🔗 [MDN: Form Element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/form)
- 🔗 [w3shools: HTML &lt;input&gt; Tag](https://www.w3schools.com/tags/tag_input.asp)
