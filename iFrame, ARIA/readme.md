# 🌐 HTML Summary

## 🧩 Basics

### 🏷 Structure of an HTML Page

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8"> <!-- UTF-8: Arabic & all languages -->
  <meta name="description" content="Page Description">
  <style> /* CSS */ </style>
  <script> /* JS */ </script>
  <title>Page Title</title>
</head>
<body>
  <!-- All page content goes here -->
</body>
</html>
📰 Text & Headings

Tag	Description

<h1> → <h6>	Headings (from large to small)
<b>	Bold text
<strong>	Important text (bold)
<i>	Italic text
<em>	Emphasized text
<mark>	Highlighted text
<u>	Underlined text
<small>	Smaller text
<del>	Deleted text
<ins>	Inserted text
<sub>	Subscript
<sup>	Superscript



---

🔗 Links

Attribute	Description

<a href="">	Link
target="_blank"	Opens link in a new tab
title=""	Tooltip description



---

📋 Lists

Tag	Description

<ul>	Unordered list
<ol>	Ordered list
<li>	List item
<dl>	Description list
<dt>	Term
<dd>	Description
Attributes: type, start, reversed	Customize order



---

📊 Tables

Tag	Description

<table>	Table
<thead> / <tbody> / <tfoot>	Table sections
<tr>	Table row
<th>	Table header cell
<td>	Table data cell
colspan	Merge columns
rowspan	Merge rows
<caption>	Table title
border, cellpadding	Table styling



---

🧱 Layout & Structure

Tag	Description

<div>	Container
<span>	Inline container
<hr>	Horizontal line
<br>	Line break


🧩 Semantic Elements

<header>, <nav>, <section>, <aside>, <footer>, <figure>, <figcaption>


---

🔊 Audio

<audio controls autoplay loop muted>
  <source src="sound.mp3" type="audio/mpeg">
  Your browser does not support the audio tag.
</audio>


---

🎬 Video

<video width="400" height="300" controls loop muted poster="poster.jpg">
  <source src="video.mp4" type="video/mp4">
  <track src="captions.vtt" kind="subtitles" srclang="en" label="English">
  Your browser does not support the video tag.
</video>


---

📝 Forms

Attribute	Description

method	How data is sent (get / post)
action	Page that receives data
required	Makes input mandatory
placeholder	Hint inside the input
readonly	Read-only (data sent)
disabled	Disabled (data not sent)
autofocus	Cursor starts here
minlength, maxlength	Character limits


📦 Input Types

text, password, email, url, file, search, date, month, time, range, number, radio, checkbox, submit, reset

🧩 Other Form Tags

<label> — For input description (for + id)

<select> — Dropdown list

<option> — List option

<optgroup> — Group inside dropdown

<textarea> — Multi-line text

<datalist> — Input with predefined options

<button> — Custom button



---

💬 Quotes & Code

Tag	Description

<q>	Inline quote
<blockquote>	Block quote (indented)
<code>	Inline code
<pre>	Preserves spaces/format
<wbr>	Word break opportunity
<bdi>	Isolates direction for mixed text
<iframe>	Embed external page
<button>	Button element



---

🧠 Global Attributes

Attribute	Description

class	Assign class name
id	Unique identifier
title	Tooltip info
hidden	Hide element
style	Inline CSS


🔒 Private Attributes

Used only in specific elements:

<img> → src, alt, width, height

<a> → href, target

<audio> / <video> → src, controls, autoplay



---

🗒 Notes

Project names should be in English

Default file name should be index.html (for GitHub Pages)

Comments in HTML:

<!-- This is a comment -->

Shortcut: Ctrl + /



---

💡 Special Characters (Entities)

Character	Entity

<	&lt;
>	&gt;



---

© Elzero-style Summary by Nada Ahmed

---

تحبي أضيف عليه شوية *ألوان أو رموز إضافية (Emoji)* في العناوين عشان يكون شكله أجمل على GitHub؟ 🌈
