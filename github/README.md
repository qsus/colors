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
LaTeX is a mathematical typesetting language. It is used to create beautiful math equations. You can use LaTeX to color text in a block like so: `$${formatting and text}$$` For example: `$${\color{red}Red\space text}$$` will result in this: $${\color{red}Red\space text}$$

|Latex code|Description|
|---|---|
|`\color{colorName}{text}`|Change color to colorName *|
|`\textcolor{colorName}{text}`|Change color to colorName *|
|`\space`|Space (normal spaces don't work)|
|`\textit{text}`|Italic|
|`\text{text}`|Normal|
|`\mathcal{text}`|Another font|
|`\mathbb{text}`|Another font|
|`\mathscr{text}`|Another font|
|`\mathfrak{text}`|Another font|
|`\mathscr{text}`|Another font|
|`\Large{text}`|Bigger font size|
|`\LaTeX`|LaTeX symbol|

\* list of color names: red, green, lightgreen, blue, lightblue, black, white, ...

Examples: todo

## Other
|Symbol|Description|Example (if possible)|Screenshot (optional)|
|---|---|---|---|
|`[text](#)`|Blue link|[text](#)|

## Sources:
- [StackOverflow question](https://stackoverflow.com/questions/11509830/)