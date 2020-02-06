---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

<form name="submitMeme" action="/thanks.html" netlify>
  <p>
    <label>Name: <input type="text" name="name" size="40"></label>
  </p>
  <p>
    <label>Email: <input type="text" name="email" size="40"></label>
  </p>
  <p>
    <label>Accept terms <input type="checkbox" name="Terms accepted"></label>
  </p>
  <p>
    <button type="submit">Send</button>
  </p>
</form>
