# Responsive images and SVG assignment

## Assignment

```{exercise}
:label: responsive-images-svg-assignment
**Learn how to do the following**:

- Use the `<picture>` element to create a responsive image with art direction.
- Use an `<img>` with `srcset` and `size` attributes to serve different image sizes for different screen widths.
- Use Dev Tools find images that are loading too slowly, and then learn to optimize them.
- Load an SVG image with `<img>`.
- Use inline SVGs and create a `<symbol>` to easily reuse your inline SVG.

**Before beginning this assignment, read**

- MDN's [Responsive images](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images)
- The info in this [Intro to SVG](https://codepen.io/lsburton/pen/ZEBYbXw?editors=1100) Codepen

**Be aware of** (*meaning you don't have to read and understand it all, but it's good to know in case you need to reference it later*)

- CSS Tricks [A Guide to the responsive images syntax in HTML](https://css-tricks.com/a-guide-to-the-responsive-images-syntax-in-html/) -- it has helpful info for beginners, but also some more advanced information.

**Review:**

- [How to code SVG icons by hand](https://www.aleksandrhovhannisyan.com/blog/svg-tutorial-how-to-code-svg-icons-by-hand/) - pro tip: set the viewbox to 120,120 so you can use whole numbers instead of decimals like in the tutorial
```

```{tip}
**Extra:**

- [Turtle graphics](https://turtleacademy.com/lessons/1) - old school programming
- [SVGOMG tool](https://jakearchibald.github.io/svgomg/) for cleaning up SVGs

**CodePens:**

- [Basic cubic Bezier curve](https://codepen.io/lsburton/pen/mdXarVr?editors=0010)
- [How cubic Bezier curves are created with de Casteljau's algorithm](https://codepen.io/lsburton/pen/jOZXyaB)
- [viewBox visualization](https://codepen.io/lsburton/pen/BaZYGKa?editors=0100)
- [SVG image filters](https://codepen.io/lsburton/pen/RvbNXj?editors=1100)
- [Color change on hover using SVG filters](https://codepen.io/lsburton/pen/NWwvNPj)
- [using a webp image in your web page](https://codepen.io/lsburton/pen/XWzrBRY?editors=1000)
- [Art direction with `<picture>`](https://codepen.io/lsburton/pen/oQywea)
- [`<picture>` HTML skeleton](https://codepen.io/lsburton/pen/rQEGxE?editors=1100)

**`<picture>` element demos:**

- [image widths displayed](https://github.com/lsburtonBYU/picture-element)
- [fullscreen images (CSS)](https://github.com/lsburtonBYU/picture-fullscreen)
```

## Rubric

````{admonition} Rubric

```{list-table}
:header-rows: 1
:name: responsive-images-svg-page-rubric
:width: 90%

* - Requirement
  - Points
* - **Repo passes all automated tests**, including validating and proofing. A description of the pretests is in the assignment README file.

    *Validator and proofer (2pts each) and 25 pretests (2pts each)*
  - 54
* - **HTML Only**

    No CSS or HTML style tags are used. If you use even one `<br>` tag you will receive a 0 on the assignment. This requirement is to help you appreciate CSS :D

  - 6
* - **Hero `<picture>` functional**

    `<picture>` element correctly loads each image at the set breakpoints. Images are sized and cropped according to assignment specifications given in assignment README.

  - 10
* - **`<img>` with srcset and sizes functional**

    `<img>` element correctly loads each image at the set breakpoints. Images are identical, except for sizes, which are explained in the assignment specifications given in assignment README.
  - 10
* - **GitHub About info**

    Include a description and link to your web page in the About section of your repo.
  - 5
```

````
