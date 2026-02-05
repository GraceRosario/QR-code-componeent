# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)

  
## Overview

### Screenshot

![](./screenshot.jpg)
<img width="1910" height="915" alt="image" src="https://github.com/user-attachments/assets/f12b7fa8-f962-4f9d-b22f-f203bdc2f154" />

### Links

- Solution URL: [solution URL here](https://github.com/GraceRosario/QR-code-componeent)
- Live Site URL: [live site URL here](https://gracerosario.github.io/QR-code-component/)


## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

imortant things I learned here as beginner were 1rem is 16px by default. rem unit is used for responsive web page. so to convert Xpx to rem, Xpx needs to be devided by 16px, as simle as that. rem is best to use when it comes to margin, padding, gap, positioning. I also learnt instead of givinging fixed width to components it is much better to use max-width and width set to 100%, this makes that certain conponent to take full width on small screens and because of max-width it takes only some part on large screens. this method is good when it coms to main components of layout like buttons, cards, etc.
Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

for example:-

```html
<article class="card">Hi! i am a card.</article>
```
```css
.card {
  max-width:300px;
  width: 100%
}
```

i also learned about semantic tags too. it's basoc structure is as seen below. <header> can furthur have <nav>. for independent content like card <article> is used. and for topic sections <section> is used.

```html
<body>
  <header></header>

  <main>
    <!-- main content -->
  </main>

  <footer></footer>
</body>
```
Sections can exist inside articles if they have their own heading.

```html
<article class="card">
  <header>
    <h3>Title</h3>
  </header>

  <section>
    <h4>Details</h4>
    <p>Extra info</p>
  </section>

  <footer>
    <p>Meta / actions</p>
  </footer>
</article>
```

Use div when, No heading, standalone meaning, Pure UI grouping

```html
<article class="card">
  <h3>Title</h3>
  <p>Text</p>

  <div class="card__extra">
    <!-- buttons, icons, price -->
  </div>
</article>
```
The rule I should memorised

article = reusable, standalone
section = topic with heading
div = visual grouping only

```html
<section>
  <h2>Cards</h2>

  <div class="card-grid">
    <article></article>
    <article></article>
  </div>
</section>

<section>
  <h2>Summary / CTA</h2>
</section>
```


