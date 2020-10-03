# Contributing

To update the documentation:

1. Fork this repository.
2. Create + edit Markdown (`.md`) files under `docs/` with a text editor.
3. Commit and create a pull request.

Pages can be organized in folders under `docs/`, with `README.md` acting as the default page for that folder.  Add a `_sidebar.md` to customize the left hand menu, else it is inherited from the parent folder.

Check the [Markdown Cheatsheet][1] for basic formatting and [Docsify Helpers][2] for extras.  Files can be [embedded][3] in pages, both to display media or inject file contents (e.g., load code sample from file).  Additional syntax is available from these plugins:

 * [docsify-tabs][4] - Tabbed content widget.
 * [docsify-katex][5] - Pretty math via [KaTeX][6].
 * [mermaid-docsify][7] - Generate charts and diagrams.

Need a text editor for Markdown?  Install [VS Code][8] use it to open the `rb-docs/` folder for a nice file tree view.  Click the Preview button in the top right for live Markdown renders!

To enable full site preview + live refresh in a web browser, follow the [quick-start guide][9] and:

 * In VS Code, click Terminal > Run Build Task (Ctrl + Shift + B).
 * Or, use the console to run `docsify serve docs` in the `rb-docs/` folder.

For help with Docsify itself, [see here][10]. This should be rare for most contributors.

[1]: https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet "Markdown Cheatsheet"
[2]: https://docsify.js.org/#/helpers "Docsify Helpers"
[3]: https://docsify.js.org/#/embed-files "Embedding Files"
[4]: https://jhildenbiddle.github.io/docsify-tabs/#/ "docsify-tabs"
[5]: https://github.com/upupming/docsify-katex "docsify-katex"
[6]: https://katex.org/ "KaTeX"
[7]: https://github.com/Leward/mermaid-docsify "mermaid-docsify"
[8]: https://code.visualstudio.com/download "Visual Studio Code"
[9]: https://docsify.js.org/#/quickstart "Docsify Quick-Start"
[10]: https://docsify.js.org/#/ "docsify.js"
