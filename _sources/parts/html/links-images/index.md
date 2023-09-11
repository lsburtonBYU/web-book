# Links and basic images

```{admonition} Objectives
**Links**

- Understand what hyperlinks, URLs, and paths are
- Understand the difference between absolute and relative links, and when to use one or the other
- Know how to write clear link text and understand how it impacts accessibility and SEO
- Be able to link to document fragments
- Understand why an optimal "touch target" is 44 x 44 pixels

**Images**

- Demonstrate image loading with the Dev Tool's waterfall chart, and understand how image size impacts page load speed
- Know how to determine image size and resolution for web pages
- Understand lazy loading and its implementation in HTML
- Be familiar with web graphic formats including JPG, PNG, GIF, and WEBP, and explain when each type is appropriate
- Know how to find, crop, and resize images, and understand image copyright laws
- Know when to use alt attribute and how to write appropriate alt text
- Identify when \<figure\> and \<figcaption\> should be used
- Understand the appropriate use of \<img\> width and height attributes
```
Watch this 3 minute Small Thing Big Idea TED video: [How the hyperlink changed everything](https://youtu.be/3Va3oY8pfSI)

Read:

- MDN's [Creating hyperlinks](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Creating_hyperlinks)
- MDS's [Images in HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML)
- CSS Trick's [A Deep Dive into Native Lazy-Loading for Images and Frames](https://css-tricks.com/a-deep-dive-into-native-lazy-loading-for-images-and-frames/) - *you don't need to enable lazy loading in browsers any more, it's baked in*

```{tip} **Hyperlinks tl;dr**

- `src="image.png"` – look in the current folder
- `src="../image.png"` – look in the parent folder (go "back" or "up" depending on how you visualize the directory structure)

Do not use
- `src="/image.png"` – *root relative*, look in the root folder; on some servers this will look in the same folder as your main index.html, but on GitHub pages, it will not work.
- `src="./image.png"` – this is the same as current folder about but is not recommend
```

```{tip} **Lazy loading tl;dr**

Add `loading="lazy"` to image tags that are *below the fold* (not visible when the page loads). This will delay loading the image until the user scrolls to it. This can significantly improve page load speed.
```

Scan:

- MDN's [\<a\> : The Anchor Element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/a) – focus on the download and target attributes. Also understand how to link to an email address and a telephone number.

- CSS Tricks: [Looking at WCAG 2.5.5 for Better Target Sizes](https://css-tricks.com/looking-at-wcag-2-5-5-for-better-target-sizes/) – this will be more relevant when we learn CSS


## Learn more

for CSS: [Enhancing The Clickable Area Size](https://ishadeed.com/article/clickable-area/)
