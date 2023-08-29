# HTML Style Guide

For this class, we will generally follow the [Google HTML/CSS Style Guide](https://google.github.io/styleguide/htmlcssguide.html).

```{note} The Google Style Guide requires indents to be two spaces. I'm not going to be strict about that. You may use tabs or spaces. All I ask is that you be consistent and that all your indents align.
```

## Basic overview of the  HTML style guide

We will deviate from the style guide and require optional closing tags on paragraphs. For example,

```{code-block} html
<p>I am a paragraph!</p>
```

NOT
```{code-block} html
<p>I am a paragraph!
```

## Summary

- Use a new line for every block, list, or table element, and indent every such child element
- Use HTML and specify `<!DOCTYPE html>`
- Use UTF-8 and specify the encoding in HTML templates and documents via `<meta charset="utf-8">`
- Use lowercase for HTML element names, attributes, attribute values
- Avoid using entity references when the Unicode character is available  –  € not `&euro;` or `&#8364;`
- Break long lines
- Use double quotes for attribute values
- Don't include spaces around the equal sign when assigning values to an attribute \
`<img src="/images/cool.jpg">ta charset="utf-8"> not <img src = "/images/cool.jpg">`

```{tip}
For guidance on general writing and how to compose headings, I recommend the [MDN Project's Writing Style Guide](https://developer.mozilla.org/en-US/docs/MDN/Contribute/Guidelines/Writing_style_guide).
```
