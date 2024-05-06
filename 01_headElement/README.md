## Elements contained in the [&lt;head&gt;](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/head) Element

<table>
  <thead>
    <th>Element</th>
    <th>Use</th>
  </thead>
  <tbody>
    <tr>
      <td>
        <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/meta"><strong>&lt;meta&gt;</strong></a> <strong>(metatags)</strong>
      </td>
      <td>
        <p>Describe metadata within an HTML document including</p>
        <ul>
          <li>Charset</li>
          <li>Author name</li>
          <li>Page description</li>
          <li>Keywords</li>
          <li>Viewport</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>
        <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/title"><strong>&lt;title&gt;</strong></a>
      </td>
      <td>
        Sets the title of the web page
      </td>
    </tr>
    <tr>
      <td>
        <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/link"><strong>&lt;link&gt;</strong></a>
      </td>
      <td>
        Defines the relationship between a document and an external resource. It is used to link the HTML document to a CSS file or to add a favicon for our web page.
      </td>
    </tr>
    <tr>
      <td>
        <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/script"><strong>&lt;script&gt;</strong></a>
      </td>
      <td>
        Used to embed executable code or data, typically JavaScript code or JSON data.
      </td>
    </tr>
  </tbody>
</table>

## Example

  ```html
  <head>
    <meta charset="UTF-8">
    <meta name="author" content="John Doe">
    <meta name="description" content="Free Web tutorials">
    <meta name="keywords" content="HTML, CSS, JavaScript">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Web Page</title>
    <link rel="icon" href="img/html5.png" type="image/x-icon">
    <link rel="stylesheet" href="css/style.css" type="text/css">
    <script defer src="js/main.js" type="text/javascript"></script>
  </head>
  ```

## Notes:
- Everything written in the head element is not seen on the web page.
- When using a scripting language other than JavaScript, you would specify its MIME type like "text/python" for Python scripts, for example.
