## Elements contained in the Header Element

<table>
  <theader>
    <th>Element</th>
    <th>Use</th>
  </theader>
  <tbody>
    <tr>
      <td><strong>metatags</strong></td>
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
        <strong>title</strong>
      </td>
      <td>
        Sets the title of the web page
      </td>
    </tr>
    <tr>
      <td>
        <strong>link<strong>
      </td>
      <td>
        Defines the relationship between a document and an external resource. It is used to link the HTML document to a CSS file or to add a favicon for our web page.
      </td>
    </tr>
  </tbody>
</table>

## Example

  ```html
  <head>
    <meta charset="UTF-8">
    <meta name="description" content="Free Web tutorials">
    <meta name="keywords" content="HTML, CSS, JavaScript">
    <meta name="author" content="John Doe">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Web Page</title>
    <link rel="icon" href="img/html5.png" type="image/x-icon">
    <link rel="stylesheet" href="css/style.css" type="text/css">
  </head>
  ```

**Note:** Everything written in the head element is not seen on the web page.
