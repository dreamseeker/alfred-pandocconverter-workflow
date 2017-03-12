# PandocConverter for Alfred 3

A workflow of Alfred 3 that converts HTML and Markdown mutually using Pandoc.

## Requirements

- Alfred 3 + Powerpack
- Perl（macOS bundled）
- Pandoc（Please install with either `Homebrew` or `Official Installer`）

## Installation

After download. Double-click the [PandocConverter.alfredworkflow](https://raw.github.com/dreamseeker/alfred-pandocconverter-workflow/master/PandocConverter.alfredworkflow), add to Alfred.

## Usage

When selected folder, you can use the Actions panel.

![ScreenShot](https://raw.github.com/dreamseeker/alfred-pandocconverter-workflow/master/screenshot.png)

### `Convert Markdown to HTML` Action

This action converts Markdown files within selected folder. And Output HTML files to `html` folder.

### `Convert HTML to Markdown` Action

This action converts HTML files within selected folder. And Output Markdown files to `md` folder.

> [note] If 'html' or 'md' folder not exists, these are auto make.

## Changelog

### 1.0.0 -- 2017.03.12

* Initial release

Brought to you by [Toru Kokubun](https://github.com/dreamseeker)
