# GitHub Markdown

<picture>
  <img alt="GitHub" src="https://github.com/developersung13/github-markdown/assets/56868605/91c8ad0b-c604-4441-b807-36715f4ec9bd" width="100px" align="right">
</picture>

Here are a few markdown additions and hints for GitHub Markdown.

Also check out [this](https://gist.github.com/seanh/13a93686bf4c2cb16e658b3cf96807f2 '@seanh/html_tags_you_can_use_on_github.md') Gist for mor information about GitHub markdown.

## Blockquotes(Beta)

### Note

```markdown
> [!NOTE]  
> Highlights information that users should take into account, even when skimming.
```

### Tip

```markdown
> [!TIP]
> Optional information to help a user be more successful.
```

### Important

```markdown
> [!IMPORTANT]
> Crucial information necessary for users to succeed.
```

### Warning

```markdown
> [!WARNING]
> Critical content demanding immediate user attention due to potential risks.
```

### Caution

```markdown
> [!CAUTION]
> Negative potential consequences of an action.
```

## Tooltips

This is how you can add your own tooltips or hover texts. You can create a tooltip by using two `##` instead of an actual link. For some reason, Markdown links that come directly after a bracket are sometimes invisible within a table. You can avoid this by linking directly to your file (For example insted of `##` use `README.md##`). The goal is to have no click effect on the tooltips. They should only look like a link so that you can more easily find the tooltip.

### Basic

```markdown
[This is an example text that looks like a link, but nothing happens when you click on it.](## 'And this is the hover text.')
```

[This is an example text that looks like a link, but nothing happens when you click on it.](## 'And this is the hover text.')

<br>

### Linebreaks

You can also create linebreaks inside your tooltip by using the `&#10;` HTML sequence.

```markdown
[Example text.](## 'Tooltip with
linebreak')
```

[Example text.](## 'Tooltip with
linebreak')

<br>

### Inside Table

You can also use tooltips inside a table, like so.

```markdown
|      A      |      B      |
| :---------: | :---------: |
| Info[\*][1] | Text[\*][2] |

[1]: ## 'Hover Info'
[2]: ## 'Hover Text'
```

|      A      |      B      |
| :---------: | :---------: |
| Info[\*][1] | Text[\*][2] |

[1]: ## 'Hover Info'
[2]: ## 'Hover Text'

## Keybindings/Keyinserts

You can insert keyboard keys into your markdown as well. To do that use the `<kbd>` and `</kbd>` tag.

### Basic

```markdown
Use <kbd>Ctrl</kbd>+<kbd>S</kbd> to save your file.
```

Use <kbd>Ctrl</kbd>+<kbd>S</kbd> to save your file.

### Nesting

[Nesting](<https://en.wikipedia.org/wiki/Nesting_(computing)> 'Nesting') is also possible.

```markdown
Hold <kbd><kbd>Ctrl</kbd>+<kbd>Shift</kbd></kbd> and press <kbd>A</kbd> to select all text.
```

Hold <kbd><kbd>Ctrl</kbd>+<kbd>Shift</kbd></kbd> and press <kbd>A</kbd> to select all text.

<br>
<br>
<br>
<br>
<br>

[↑ Back to top](#)

```

```
