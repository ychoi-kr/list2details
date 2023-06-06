# Markdown to HTML Details Converter

## Overview
This web application takes markdown input, specifically a markdown list, and converts it into HTML code wrapped in details and summary tags. It's ideal for creating a toggleable list in HTML that initially displays a summary and then displays a list of details when clicked.

## Usage
1. Navigate to [https://ychoi-kr.github.io/list2details/](https://ychoi-kr.github.io/list2details/)
2. In the left textarea, input your markdown text. The first line should be the summary (title) of the list, followed by the list items, each starting with a dash (`-`).
3. Optionally, you can select the checkbox to decide whether the `details` tag should be `open` by default and whether to include CSS to change the cursor style when hovering over the `summary`.
4. The converted HTML will automatically appear in the right textarea. You can copy the HTML code by clicking the "Copy HTML" button.
5. You can clear the input and output fields by clicking the "Clear Input" button.

## Example
Markdown input:
```
‘-없이’로 끝나는 단어

- [값없이](http://example.com/1)
- 관계없이
- 거침없이
- 기탄없이
```
HTML output:
```
<details open>
  <summary>‘-없이’로 끝나는 단어</summary>
  <ul>
    <li><a href="http://example.com/1">값없이</a></li>
    <li>관계없이</li>
    <li>거침없이</li>
    <li>기탄없이</li>
  </ul>
</details>
```
Enjoy converting your markdown lists to HTML details!
