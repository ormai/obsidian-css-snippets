# Snippets

### Drop caps

This snippet implements [drop caps](https://en.wikipedia.org/wiki/Initial) in Obsidian. It works by assigning a specific font to a character which has been given the `dcaps` class:

```html
<span class="dcaps">I</span>
```

![dropcaps](media/drop-caps.png)

This was inspired by [gwern.net](https://gwern.net/design#principles).

### Article

Scientific papers, blogposts, excerpts, etc., need to have a different style than the common note. `article.css` applies a custom font, shrinks the reading length, centers the headings and tones down the color palette.

Syntax:

```yaml
---
cssclass: article
---
```

![article](media/article.png)
