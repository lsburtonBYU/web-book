# HTML template

You must use the following template for your HTML files

```{code-block} html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Add a short description fo your page here">
    <title>Document</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/normalize/8.0.1/normalize.min.css">
</head>
<body>

</body>
</html>
```

```{tip}
The video at the bottom of this page steps through this process and also shows how to use VS Code snippets to streamline the process.
```

## Generate this template in VS Code

Use VS Code's built-in Emmet tool to generate the template.

### Create a new HTML file

Create a new file and save it with an `.html` extension. *Emmet won't work unless a file has an* `.html` *extension.*

```{image} /images/html/create-file.gif
:alt: Create a new file
:width: 600px
```

### Generate the template with Emmet

Start typing `html` and Emmet will give you suggestions. Select `html:5` and hit `TAB`.

```{image} /images/html/emmet-html.gif
:alt: generate an html template with Emmet
:width: 600px
```

```{tip}
HINT: an even faster way to generate this template is by typing `!` and hitting `TAB`.
```

```{image} /images/html/emmet-exclaim.gif
:alt: generate an html template with Emmet ! shortcut
:width: 600px
```

### Add a title and description

Change the content inside the `<title>` tags to your web page title.

Add a `<meta>` description tag. Use Emmet to add the meta tag. Type `meta`, select `meta:desc`, and press `TAB`

```{image} /images/html/emmet-meta-desc.gif
:alt: use Emmet to add a meta description tag
:width: 600px
```

```{tip}
Add a description of your site in the value of the `content` attribute; use 150 characters or less. This value, and the page `<title>` text will show up on search engine results describing the page.
```

### Add a CSS reset file

Once we start using CSS, you need to add a link to `normalize.css`. I'd suggest adding it to your first assignment, since we will eventually add CSS to that file.

To add `normalize.css`, paste this line into your `<head>` element:

```{code-block} html
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/normalize/8.0.1/normalize.min.css">
```

or find the link by googling "normalize cdn" or copy the link directly from the normalize repository: [https://cdnjs.com/libraries/normalize](https://cdnjs.com/libraries/normalize)

You can streamline this process by creating a VS Code Snippet, which I demo at the end of the video below.

## Video instructions

```{topic} Watch
<iframe width="560" height="315" src="https://www.youtube.com/embed/YOZiusATN78?si=EVPVyAMONrfyXrqr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
```
