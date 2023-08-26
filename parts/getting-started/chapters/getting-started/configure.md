# Configure VS Code

## Intro to VS Code editor

Watch the video below, **Learn Visual Studio Code in 7mins**.

```{topic} Watch
<iframe width="560" height="315" src="https://www.youtube.com/embed/B-s71n0dHUk?si=rX2f6ZNpiFT_FkmM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
```

```{note}
We will use **Live Server** for viewing web pages instead of the **Live Preview** extension shown in the video
```

## Install extensions and configure settings

Next, watch the demo video I created below to learn how to install the extensions required for the course and configure your User Settings JSON file. The extensions and JSON snippet are below the video.

```{topic} Watch
<iframe width="560" height="315" src="https://www.youtube.com/embed/WAyHcvpgDZM?si=sAHhDVhGZhljSwzc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
```

```{note}
The HTMLHint extension has changed, so install the one authored by HTMLHint, not the one authored by ctf0 that I show in the video. Also not in the video, install the **Markdown Preview Github Styling** extension. See the extension list below.
```

## Extensions

### Make code look nice

- **Prettier - Code formatter** by Prettier

### Avoid errors

- **Code Spell Checker** by Street Side Software
- **stylelint** by stylelint
- **HTMLHint** by HTMLHint ← This is different than what I show in the video; it took awhile for this extension to stabilize.
- **a11y-kit** by MicroFish

### Utilities

- **Image Preview** by Kiss Tamás
- **Live Server** by Ritwick Dey
- **Markdown Preview Github Styling** by Matt Bierner ← not in the video, but needed for using Github Classroom for assignments

## Set Firefox as default browser

To set Firefox as your live server default browser and to set your default formatters (I don't like using Prettier on HTML), choose the command **Preferences: Open User Settings (JSON)** and paste the following into settings.json:

```{code-block} json
{
  "liveServer.settings.CustomBrowser": "firefox",
  "cSpell.dictionaries": ["lorem-ipsum"],
  "editor.linkedEditing": true,
  "editor.tabSize": 2,
  "editor.formatOnSave": true,
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "[html]": {
    "editor.defaultFormatter": "vscode.html-language-features"
  }
}
```
