## Markdown Preview

A [Brackets](https://github.com/adobe/brackets) extension that provides a live preview of markdown documents. 

### Installation

* Select **File > Extension Manager...** (or click the "brick" icon in the toolbar)
* Click **Install from URL...**
* Enter the url of this repo: 
 * For Brackets Sprint 28 (or later): https://github.com/dtinth/brackets-MathJaxMarkdownPreview
* Click **Install**

### Difference from [gruehle/MarkdownPreview](https://github.com/gruehle/MarkdownPreview)

* MathJax with \\( and \\) and $$.
* Sans-serif font by default.
* Preview on save (no live preview).

### How To Use
When a markdown document (with extension ".md" or ".markdown") is open, a markdown icon is shown in the 
toolbar at the top of the Brackets window. Click this icon to open the preview panel. The panel can be 
resized vertically.

The preview is updated when you save the document. You can hover over links to see the href in a tooltip.

### Credits
This extension uses the following open source components:

* [Marked](https://github.com/chjj/marked) - A markdown parser written in JavaScript
* [markdown-css-themes](https://github.com/jasonm23/markdown-css-themes) - This extension uses the "Swiss" theme
* [markdown-mark](https://github.com/dcurtis/markdown-mark) - The icon used in the toolbar
