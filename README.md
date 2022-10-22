# A website built from scratch

- HTML
- CSS
- Wireframes
- git
- Markdown

## HTML

I started creating the skeleton (! + Enter in VSCode), then we created the header, linked the CSS and also the other two big containers, main and footer.

Header contains a logo, a heading and a navigation menu.

```html
<header>
  <div class="logo">
    <p>My Logo</p>
  </div>
  <h1>Personal Training</h1>
  <nav class="nav-items">
    <a href="">Training</a>
    <a href="">About Us</a>
    <a href="">Contact</a>
  </nav>
</header>
```

## CSS

Defined primary and secondary colours, added them to the background and text colours.

Flexbox for the header to align the three elements inisde centred and vertically.

```css
header {
  background-color: #ebd4cf;
  display: flex;
  flex-direction: column;
  align-items: center;
}
```  

## Wireframes

!["Figma View"](./Images/Screen%20Shot%202022-10-22%20at%201.31.49%20pm.png)