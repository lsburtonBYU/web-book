# Required software

We will be using the following applications in the class. If you don't already have them on your computer, please download and install the following:

## Visual Studio Code

```{image} /images/vs-code.png
:height: 100px
:name: vs-code
```

[Visual Studio Code](https://code.visualstudio.com/) is the code editor that we will use to write the HTML and CSS for our websites.

## Firefox

```{image} /images/firefox-logo.png
:height: 100px
:name: Firefox
```

[Firefox](https://www.mozilla.org/en-US/firefox/new/) has the best CSS dev tools, so we will use it as our main browser to debug our websites.

## Google Chrome

```{image} /images/chrome-logo.png
:height: 100px
:name: Chrome
```

[Chrome](https://www.google.com/chrome/) has some dev tool features that are better than Firefox's, so it's good to have both browsers installed. It's helpful to test sites in multiple browsers.

```{tip}
Avoid using Safari for now. Safari is breaking from some web standards. If you prefer to have Safari as your default browser, you can set VS Code to open web pages in Firefox.
```

## Git

```{image} /images/git-logo.png
:height: 100px
:name: Git
```

[Git](https://git-scm.com/) is a version control system that we will use to manage our code. It's a good idea to use version control for any code you write, even if you're the only one working on it. It's especially important when you're working with a team.

Here's a 7 minute video showing how to install and configure Git

```{topic} Watch
<iframe width="560" height="315" src="https://www.youtube.com/embed/zshf_32xbsI?si=e6or2Q9T_Rrwybw2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
```

```{note}
Notes from the video:

- [Mac installer](https://sourceforge.net/projects/git-osx-installer/)- for other options such as Homebrew, see Git's [Download for Mac](https://git-scm.com/download/mac) page
- [Windows installer](https://git-scm.com/download/win) - select the first option, "Click here to download"

For info on other installs see [Getting Started - Installing Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

Make sure to run these commands in terminal

```{code-block} bash
git config --global user.name “your name”

git config --global user.email email-address

git config --global init.defaultBranch main
```
