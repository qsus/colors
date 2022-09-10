# Github
Github is a web-based Git repository hosting service. This guide will show you how to make markdown files colorfull, beacuse sadly, GitHub blocks coloring using style="color: color;".

## Basic text formatting
|Symbol|Description|Example (if possible)|Screenshot (optional)|
|---|---|---|---|
|`*text* or _text_`|Italic|*italic*|
|`**text** or __text__`|Bold|**bold**|
|`~~text~~`|Strikethrough|~~strikethrough~~|
|`* list`|Unordered list||
|`1. list`|Ordered list||


## Emojis
⚪ ⬜ 🤍 white  
🔴 🟥 ❤️ red  
🟠 🟧 🧡 orange  
🟡 🟨 💛 yellow  
🟢 🟩 💚 green  
🔵 🟦 💙 blue  
🟣 🟪 💜 purple  
🟤 🟫 🤎 brown  
⚫ ⬛ 🖤 black  

## Diff highlighting
```
```diff
see below
\```
```

```diff
+ green
- red
! orange
# gray
@@ blue @@
```

## Note and Warning tags
> __Note__: This is a note using `> __Note__`.

> __Warning__: This is a warning using `> __Warning__`.

## LaTeX coloring
LaTeX is a mathematical typesetting language. It is used to create beautiful math equations. You can use LaTeX to color text in a block like so: `$${formatting and text}$$` { and } symbols are propably optional. Note that the text is not selectable and is always centered, unless you use inline version with only one $ symbol. See below the table for examples.

|Latex code|Description|
|---|---|
|`\color{colorName}text`|Change color to colorName *|
|`\color{colorName}{text}`|Change color to colorName *|
|`\textcolor{colorName}{text}`|Change color to colorName *|
|`\space`|Space (normal spaces don't work)|
|`\textit{text}`|Italic|
|`\text{text}`|Normal|
|`\mathcal{text}`|Another font|
|`\mathbb{text}`|Another font|
|`\mathscr{text}`|Another font|
|`\mathfrak{text}`|Another font|
|`\large{text}`|Bigger font size|
|`\Large{text}`|Even bigger font size|
|`\LaTeX`|LaTeX symbol|
|`\colorbox{color}{text}`|Colored box around the text *|
|`\fbox{text}`|Box around the text|

\* list of color names: red, green, lightgreen, blue, lightblue, black, white, ... You can also use custom RGB with `\color[RGB]{red, green, blue}{text}`. If you use capital RGB, the individual colors levels are integers 0-255 inclusive. If you use small rgb, they are 0-1. You can also use `grey` and number 0-1 to choose how light it will be.

### Examples:
Colors `$${\textcolor{red}{red}\space \color{green}{green}\space \color{blue}blue}$$`: $${\textcolor{red}{red}\space \color{green}{green}\space \color{blue}blue}$$
Font styles `$${default\space\text{normal}\space\textit{italic}}$$`: $${default\space\text{normal}\space\textit{italic}}$$
Font families `$${\mathcal{mathcal}\space\mathbb{mathbb}\space\mathscr{mathscr}\space\mathfrak{mathfrak}}$$`: $${\mathcal{mathcal}\space\mathbb{mathbb}\space\mathscr{mathscr}\space\mathfrak{mathfrak}}$$
Boxes `$${\colorbox{lightgreen}{\color{black}{lightgreen box with black text}}\space\fbox{fbox}}$$`: $${\colorbox{lightgreen}{\color{black}{lightgreen box with black text}}\space\fbox{fbox}}$$
Custom RGB `$${\color[RGB]{0, 255, 0}{lime}\color[rgb]{1, 0 , 1}{purple}\color[gray]{0.5}{dim red}}$$`: $${\color[RGB]{0, 255, 0}{lime}\space\color[rgb]{1, 0 , 1}{purple}\space\color[gray]{0.5}{gray}}$$
Other `$${\LaTeX\space default\space\large{large}\space\Large{Large}}$$`: $${\LaTeX\space default\space\large{large}\space\Large{Large}}$$
Inline example `lorem ${\color{yellow}ipsum}$ dolor`: lorem ${\color{yellow}ipsum}$ dolor

## Other
|Symbol|Description|Example (if possible)|Screenshot (optional)|
|---|---|---|---|
|`[text](#)`|Blue link|[text](#)|

## Sources:
- [StackOverflow question](https://stackoverflow.com/questions/11509830/)
- [GitHub Issue 369](https://github.com/github/markup/issues/369)
- [GitHub Issue 1440](https://github.com/github/markup/issues/1440)