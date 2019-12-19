# DOM

### DOM

|  |  |
| :--- | :--- |
| console |  |
| document |  |
| window |  |
| node |  |
| getters / setters |  |

|  |  |
| :--- | :--- |
| elements | [https://developer.mozilla.org/en-US/docs/Web/API/Element](https://developer.mozilla.org/en-US/docs/Web/API/Element) |
| methods |  |
| properties |  |
| classes |  |
| data attributes |  |

### Element Properties and Methods

<table>
  <thead>
    <tr>
      <th style="text-align:left"></th>
      <th style="text-align:left"></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">.createContextualFragment()</td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">.createRange()</td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left"><a href="https://developer.mozilla.org/en-US/docs/Web/API/Element/classList">Element.classList()</a>
      </td>
      <td style="text-align:left">The <b><code>Element.classList</code></b> is a read-only property that returns
        a live <a href="https://developer.mozilla.org/en-US/docs/Web/API/DOMTokenList"><code>DOMTokenList</code></a> collection
        of the <code>class</code> attributes of the element. This can then be used
        to manipulate the class list.</td>
    </tr>
    <tr>
      <td style="text-align:left"><a href="https://developer.mozilla.org/en-US/docs/Web/API/Document/getElementById">.getElementbyId()</a>
      </td>
      <td style="text-align:left">The <a href="https://developer.mozilla.org/en-US/docs/Web/API/Document"><code>Document</code></a> method <b><code>getElementById()</code></b> returns
        an <a href="https://developer.mozilla.org/en-US/docs/Web/API/Element"><code>Element</code></a> object
        representing the element whose <a href="https://developer.mozilla.org/en-US/docs/Web/API/Element/id"><code>id</code></a> property
        matches the specified string. Since element IDs are required to be unique
        if specified, they&apos;re a useful way to get access to a specific element
        quickly.</td>
    </tr>
    <tr>
      <td style="text-align:left"><a href="https://developer.mozilla.org/en-US/docs/Web/API/Element/innerHTML">.innerHTML()</a>
      </td>
      <td style="text-align:left">The <a href="https://developer.mozilla.org/en-US/docs/Web/API/Element"><code>Element</code></a> property <b><code>innerHTML</code></b> gets
        or sets the HTML or XML markup contained within the element.</td>
    </tr>
    <tr>
      <td style="text-align:left"><a href="https://developer.mozilla.org/en-US/docs/Web/API/HTMLElement/innerText">.innerText()</a>
      </td>
      <td style="text-align:left">The <b><code>innerText</code></b> property of the <a href="https://developer.mozilla.org/en-US/docs/Web/API/HTMLElement"><code>HTMLElement</code></a> interface
        represents the &quot;rendered&quot; text content of a node and its descendants.
        As a getter, it approximates the text the user would get if they highlighted
        the contents of the element with the cursor and then copied it to the clipboard.</td>
    </tr>
    <tr>
      <td style="text-align:left">.insertAdjacentText()</td>
      <td style="text-align:left">
        <p></p>
        <ul>
          <li><code>&apos;beforebegin&apos;</code>: Before the <code>element</code> itself.</li>
          <li><code>&apos;afterbegin&apos;</code>: Just inside the <code>element</code>,
            before its first child.</li>
          <li><code>&apos;beforeend&apos;</code>: Just inside the <code>element</code>,
            after its last child.</li>
          <li><code>&apos;afterend&apos;</code>: After the <code>element</code> itself.</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">.outerHTML()</td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">.textContent()</td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left"><a href="https://developer.mozilla.org/en-US/docs/Web/API/Document/querySelector">.querySelector()</a>
      </td>
      <td style="text-align:left">The <a href="https://developer.mozilla.org/en-US/docs/Web/API/Document"><code>Document</code></a> method <b><code>querySelector()</code></b> returns
        the first <a href="https://developer.mozilla.org/en-US/docs/Web/API/Element"><code>Element</code></a> within
        the document that matches the specified selector, or group of selectors.
        If no matches are found, <code>null</code> is returned.</td>
    </tr>
    <tr>
      <td style="text-align:left">.querySelectorAll()</td>
      <td style="text-align:left"></td>
    </tr>
  </tbody>
</table>### Attributes

|  |  |
| :--- | :--- |
| .dataset\(\) |  |
| .getAttribute\(\) |  |
| .hasAttribute\(\) |  |
| [.setAttribute\(\)](https://developer.mozilla.org/en-US/docs/Web/API/Element/setAttribute) |  |

### HTML

|  |  |
| :--- | :--- |
| [.appendChild\(\)](https://developer.mozilla.org/en-US/docs/Web/API/Node/appendChild) |  |
| .cloneNode\(\) |  |
| [.createElement\(\)](https://developer.mozilla.org/en-US/docs/Web/API/Document/createElement) | In an HTML document, the document.createElement\(\) method creates the HTML element specified by tagName, or an HTMLUnknownElement if tagName isn't recognized. |
| .insertAdjacentElement\(\) |  |

### Events

|  |  |
| :--- | :--- |
| .addEventListener\(\) | 'load' |
