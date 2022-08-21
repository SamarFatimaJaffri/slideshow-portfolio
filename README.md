# Samar Fatima Jaffri - Slideshow Portfolio
This website include my precise portfolio. Through this portfolio one can get my Bio and Contact info.

<details>
<summary> Reveal.js Info </summary>

## Horizontal v/s Vertical Slides:
### Horizontal Slides:
Create Horizontal slides by,
- Find the `<div>` elements having `class="slides"`
- Create a sepearate `<section>` for each slide inside that `<div>`
```
<div class="reveal">
  <div class="slides">
    <section>Slide1</section>
    <section>Slide2</section>
  </div>
</div>
...
```

### Vertical Slides:
Create vertical slides by,
- Find the `<div>` elements having `class="slides"`
- Create a `<section>` inside the `<div>` for all the verticle slides
- Create a `<section>` inside the `<section>` for each vertical slide
```
<div class="reveal">
  <div class="slides">
    <section>
      <section>Slide1</section>
      <section>Slide2</section>
    </section>
  </div>
</div>
```
I have used vertical slides for this project.

---
</details>

### The Slides are made using:
- Video in slides are made using [Canva](https://www.canva.com/)
- Slides are made using [Reveal.js](https://revealjs.com/)
