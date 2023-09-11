# Semantic HTML assignment

## Assignment

```{exercise}
:label: semantic-html-assignment
**Create HTML pages using semantic markup. Include a navigation menu that links to two subpages.**

Before beginning this assignment, read the [Semantic HTML](../semantic-html/index.md), [Accessibility basics](../accessibility/index.md), and [Links and basic images](../links-images/index.md) pages.
```

```{tip}
Some references from the assignment

**Semantic HTML**
- See w3school's [HTML semantic elements](https://www.w3schools.com/html/html5_semantic_elements.asp) for a helpful summary and list of tags.[^footnote-w3s]

[^footnote-w3s]: w3schools is not a great resource for learning web development (too much outdated or incorrect info), and I don't normally recommend it, but they do have some helpful reference pages.

- Read the individual element's pages on MDN in the list in their [Semantics in HTML](https://developer.mozilla.org/en-US/docs/Glossary/Semantics#semantics_in_html) section.

**Images**

- Read a11y collective's [How to write great alt text](https://www.a11y-collective.com/how-to-write-great-alt-text/) for tips on writing good alt text for images.

- To understand why I require HTML `width` and `height` attributes set to an image's intrinsic width, reference Smashing Magazine's [Setting Height And Width On Images Is Important Again](https://www.smashingmagazine.com/2020/03/setting-height-width-images-important-again/).

**Links**

- Read MDN's [A quick primer on URLs and paths](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Creating_hyperlinks#a_quick_primer_on_urls_and_paths) for a review of relative links.
````

## Rubric

````{admonition} Rubric

```{list-table}
:header-rows: 1
:name: semantic-html-rubric
:width: 90%

* - Requirement
  - Points
* - **Repo passes all automated tests**, including validating and proofing. A descriptions of the pretests is in the assignment README file.

    *Validation (3pts) and a proofer test (2pts) and 25 pretests (2pts each)*
  - 55
* - **Readability**

    HTML source follows the [HTML/CSS Style Guide for the course](../html-basics/style-guide.md).

    *Basically this means you should have formatters installed so your code is properly formatted.*

  - 5
* - **HTML only**

    No CSS or HTML style tags are used. If you use even one `<br>` tag you will receive a 0 on the assignment :D

    *I'm breaking bad habits early. No `<br>` tags are allowed in this course.*[^footnote-br]

    [^footnote-br]: I'm being overly strict, but I want you to get in the habit of using CSS for layout and spacing.  `<br>` tags have some use, but I maintain you can build a website without them. If you want to use them, you can, but you will receive a 0 on the assignment.

  - 5
* - **Navigation links are functional**

    Navigation links between the Home page and the About and Contact pages are functional. A pretest checks that relative links are used.

  - 10
* - **GitHub About info**

    Include a description and link to your web page in the About section of your repo.
  - 5
```
````
