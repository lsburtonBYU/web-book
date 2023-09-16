# CSS topic presentation assignment

## Assignment

```{exercise}
:label: css-topic-svg-assignment
**Create a web page that illustrates how to use a CSS feature.**

- [Sign up for one of the following CSS topics](https://docs.google.com/spreadsheets/d/1tRk_Q40l3GPYnLau3PKWn5ery1MuUOup3e1WEX-NvSo/edit?usp=sharing).

- Research the topic at the resources listed below (and other sources, if you find them) and then create a web page with [embedded CodePens](https://blog.codepen.io/documentation/features/embedded-pens/) to illustrate your topic.

- Prepare a 5- to 10-minute informal presentation on the topic. Topics will be presented in class.

I created a sample page, [Background clip text](https://burtonbyu.com/css-topic/) to demo the what I'm looking for in this assignment. The focus on this assignment is an oral presentation, but give enough written description on your web page so that students can refer back to your topic as a refresher.


Find and read about your topic on each of these websites:

- [W3C Schools Online Web Tutorials](https://www.w3schools.com/)[^w3schools]
- [MDN Web Docs](https://developer.mozilla.org/en-US/)
- [CSS Tricks](https://css-tricks.com/)

[^w3schools]: W3Schools is not affiliated with the W3C. It's a good resource for beginners, but it's not always accurate. It's best to use it as a starting point for your research and then verify what you learn on other sites.
```

````{tip}
**CSS to vertically center content on web page**

For the CSS topic, if you would like to vertically center your page.

If your webpage is set up as:
```{code-block} html
<body>
  <main>
    <article>
      .....
```

To vertically center the `<article>` content, you can add the following to your `<head>` :

```{code-block} css
<style>

main {
  display: flex;
  flex-direction: column;
  align-items: center;
}

article {
  max-width: 48rem; /* choose whatever width you'd like.
                      "em" can be viewed as the width
                       of a font's M character */
}

</style>
```
````

## Rubric

````{admonition} Rubric

```{list-table}
:header-rows: 1
:name: css-topic-rubric
:width: 90%

* - Requirement
  - Points
* - **Clean web page**

    Web page has a clean design, is easily readable, and pens are embedded correctly.

  - 10
* - **Basic information**

    Page includes information about the topic from the required websites

  - 20
* - **Clear Codepen examples**

    Page uses clear and informative Codepen examples to illustrate topic

  - 10
* - **Thoughtful presentation**

    Student obviously researched the topic well and thoughtfully created the page and Codepen examples.
  - 10
```

````
