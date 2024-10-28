# Open links in new tab Extension For Quarto

This Quarto extension will make all links in your Quarto project open in a new tab. 

## Installing

Install this extension in your Quarto project by running the following in the terminal: 

```bash
quarto add melissavanbussel/open-links-new-tab
```

This will install the extension under the `_extensions` subdirectory.
If you're using version control, you will want to check in this directory.

## Using

After installing the extension for your project, activate it by adding the following to your Quarto document YAML: 

```
---
title: "My Document"
format: html
filters:
  - open-links-new-tab
```

## Example

Here is the source code for a minimal example: [example.qmd](example.qmd).