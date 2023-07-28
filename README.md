
# A Minimal Dark Theme for Visual Studio Code

## Description

One Dark Minimal is a sleek and modern dark theme designed for Visual Studio Code. It is based on the popular "One Dark Pro" theme, with the main objective of providing a minimalistic and clean appearance to the Visual Studio Code editor.

![One Dark Minimal Preview](https://raw.githubusercontent.com/MrRevillod/OneDarkMinimal/main/img/preview.png)

## Features

- Clean and minimal design, reducing distractions while coding.
- Based on the renowned "One Dark Pro" theme, providing a polished and professional look.
- Carefully selected colors to ensure optimal readability and comfort during long coding sessions.


## Recommended Extensions

To further enhance your experience with One Dark Minimal, I recommend using the following icon themes:

- File Icon Theme: [Symbols](https://github.com/miguelsolorio/vscode-symbols)
- Product Icon Theme: [Fluent Icons](https://github.com/miguelsolorio/vscode-fluent-icons)

## Better experience

If you want a more minimal environment, consider using the following configurations:

```json
// Show icons for expanding and collapsing folders in the explorer.
"symbols.hidesExplorerArrows": false,

// Show inline suggestions while typing.
"editor.inlineSuggest.enabled": true,

// Disable the Minimap.
"editor.minimap.enabled": false,

// Disable file preview when clicking on them in the sidebar.
"workbench.editor.enablePreview": false,


// Set the icon theme for product icons.
"workbench.productIconTheme": "fluent-icons",

// Set the icon theme for explorer and sidebar icons.
"workbench.iconTheme": "symbols",

// Disable Breadcrumbs.
"breadcrumbs.enabled": false,

// Hide vertical and horizontal scrollbars.
"editor.scrollbar.vertical": "hidden",
"editor.scrollbar.horizontal": "hidden",

// Disable scrolling beyond the last line.
"editor.scrollBeyondLastLine": false,

// Set the number of additional columns beyond the content of the longest line that the editor should allow scrolling.
"editor.scrollBeyondLastColumn": 0,

// Enable smooth scrolling of the editor.
"editor.smoothScrolling": true,

// Set the cursor blinking type.
"editor.cursorBlinking": "smooth",

// Hide the line separating the main editor and the secondary sidebar.
"editor.overviewRulerBorder": false,
