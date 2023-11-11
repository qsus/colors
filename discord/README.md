# Discord
Discord is a platform for text and voice communication. It is a popular platform for gamers and programmers. Discord uses markdown for formatting text. This guide will show you how to format text in Discord. (Intro written by GitHub Copilot)

## Text formatting basics
|Symbol|Description|Example (if possible)|Screenshot (optional)|
|---|---|---|---|
|`*text* or _text_`|Italic|*italic*|
|`**text**`|Bold|**bold**|
|`~~text~~`|Strikethrough|~~strikethrough~~|
|`__text__`|Underline|__underline__|
|\`text\`|Inline code|`code`|
|` ```text``` `|Multiline code block|```code```|
|`> text`|Quote||
|`>>> text`|Blockquote||
## Code blocks color formatting
This feature is originally indended for syntax highlighting. However, you can use it to color your text. Because it's way too complicated to describe here, here is [link to Matthews explanation](https://gist.github.com/matthewzring/9f7bbfd102003963f9be7dbcf7d40e51).
(to do: add example image here)
## ANSI code block formatting
Discord added support for custom color formatting inside code blocks by supporting ascii escape codes. This is a much more powerful than syntax highlihting, but also more complicated. Here is a [link to a kkrypt0nns guide](https://gist.github.com/kkrypt0nn/a02506f3712ff2d1c8ca7c9e0aed7c06). (to do: add example image here)
## Slash command highlighting (in testing)
String `</yourText:anyInt>` in discord message will become blueish, sort of like when you ping someone. It can be used to highlight some text. YourText is any text, using only alphanumerical characters, -, _ and space. AnyInt is any natural number; it doesn't seem to have any influence on the final effect. Note that only the part `/yourText` will be displayed.

Example: `</imposter is sus:1>`: "/imposter is sus" with blue background.

Tested 2023-10-15, doesn't work.
## Hypertext formatting
Discord now allows hypertext links using the following syntax: `[displayed text](URL)`. For example `[example](https://example.com/)` will result in [example](https://example.com/). URL has to have http or https scheme specified. Discord will show "Leaving Discord" screen, unless the domain is whitelisted. This means Discord will not ask when the target URL is a discord.gg invite.
## @silent
When "@silent" is present in the beginning of a message, Discord will hide it and mark the message as silent. A bell will be shown next to the message timestamp and nobody will get pinged, even if mentioned in the message.
## TODO:
- add stuff from [this list from matthewzring](https://gist.github.com/matthewzring/9f7bbfd102003963f9be7dbcf7d40e51)
## Sources:
- [Discord FAQ](https://support.discordapp.com/hc/en-us/articles/210298617-Markdown-Text-101-Chat-Formatting-Bold-Italic-Underline-)
- [Rebane Discord Colored Text Generator](https://rebane2001.com/discord-colored-text-generator/)
- [ANSI Discord colors guide](https://gist.github.com/kkrypt0nn/a02506f3712ff2d1c8ca7c9e0aed7c06)
- [Discord Markdown Tutorial](https://gist.github.com/matthewzring/9f7bbfd102003963f9be7dbcf7d40e51)
