<!-- # HTML5 Tags - Complete List with Explanations

This README contains the complete list of **all ~145 HTML5 tags** (including obsolete ones) explained in simple words, so students and beginners can easily learn. You can also copy them directly for practice.

---

## 🏗️ Basic Structure
- **`<!DOCTYPE>`** → Declares the document as HTML5.
- **`<html>`** → Root element of the page.
- **`<head>`** → Contains metadata, title, and links.
- **`<title>`** → Sets the title in the browser tab.
- **`<body>`** → Main content visible to users.

---

## 📝 Metadata
- **`<base>`** → Base URL for relative links.
- **`<link>`** → Connects external CSS, icons, etc.
- **`<meta>`** → Extra info like charset, description.
- **`<style>`** → Defines internal CSS rules.

---

## 📑 Sectioning
- **`<header>`** → Top section with logo/nav.
- **`<footer>`** → Bottom section (copyright).
- **`<nav>`** → Navigation menus.
- **`<article>`** → Independent content (blog post).
- **`<section>`** → Thematic grouping of content.
- **`<aside>`** → Sidebar/related info.
- **`<address>`** → Contact details.
- **`<main>`** → Main unique content.
- **`<h1>` → `<h6>`** → Headings.
- **`<hgroup>`** → Groups multiple headings.

---

## 📦 Grouping Content
- **`<div>`** → Generic container.
- **`<p>`** → Paragraph.
- **`<hr>`** → Horizontal line.
- **`<pre>`** → Preformatted text.
- **`<blockquote>`** → Block of quoted text.
- **`<ol>`** → Ordered list.
- **`<ul>`** → Unordered list.
- **`<li>`** → List item.
- **`<dl>`** → Description list.
- **`<dt>`** → Term in description list.
- **`<dd>`** → Definition in description list.
- **`<figure>`** → Groups media with caption.
- **`<figcaption>`** → Caption for figure.

---

## 🔤 Text-Level Semantics
- **`<a>`** → Hyperlink.
- **`<abbr>`** → Abbreviation.
- **`<b>`** → Bold (no importance).
- **`<bdi>`** → Isolates text direction.
- **`<bdo>`** → Overrides text direction.
- **`<br>`** → Line break.
- **`<cite>`** → Reference to a work.
- **`<code>`** → Code snippet.
- **`<data>`** → Machine-readable value.
- **`<dfn>`** → Defining term.
- **`<em>`** → Emphasis (italic).
- **`<i>`** → Italic (alternate voice).
- **`<kbd>`** → Keyboard input.
- **`<mark>`** → Highlighted text.
- **`<q>`** → Inline quote.
- **`<rp>`** → Fallback for ruby.
- **`<rt>`** → Ruby annotation text.
- **`<ruby>`** → Ruby annotations (Asian languages).
- **`<s>`** → Strikethrough.
- **`<samp>`** → Program output.
- **`<small>`** → Smaller text.
- **`<span>`** → Inline container.
- **`<strong>`** → Important text (bold).
- **`<sub>`** → Subscript.
- **`<sup>`** → Superscript.
- **`<time>`** → Date/time.
- **`<u>`** → Underlined text.
- **`<var>`** → Variable name.
- **`<wbr>`** → Word break opportunity.

---

## ✏️ Edits
- **`<del>`** → Deleted text.
- **`<ins>`** → Inserted text.

---

## 🎵 Embedded Content
- **`<area>`** → Clickable area in image map.
- **`<audio>`** → Audio file.
- **`<img>`** → Image.
- **`<map>`** → Image map.
- **`<track>`** → Captions/subtitles.
- **`<video>`** → Video.

---

## 🎨 SVG and MathML
- **`<svg>`** → Vector graphics.
- **`<math>`** → Math notation.

---

## 📊 Tables
- **`<table>`** → Table.
- **`<caption>`** → Table title.
- **`<colgroup>`** → Group of columns.
- **`<col>`** → Column properties.
- **`<tbody>`** → Table body.
- **`<thead>`** → Table header.
- **`<tfoot>`** → Table footer.
- **`<tr>`** → Row.
- **`<td>`** → Data cell.
- **`<th>`** → Header cell.

---

## 📝 Forms
- **`<form>`** → Input form.
- **`<fieldset>`** → Groups fields.
- **`<legend>`** → Caption for fieldset.
- **`<label>`** → Label for input.
- **`<input>`** → Input field.
- **`<button>`** → Button.
- **`<select>`** → Dropdown.
- **`<datalist>`** → Autocomplete options.
- **`<optgroup>`** → Group of options.
- **`<option>`** → Dropdown option.
- **`<textarea>`** → Multi-line input.
- **`<output>`** → Calculation result.
- **`<progress>`** → Progress bar.
- **`<meter>`** → Measurement gauge.

---

## 🖱️ Interactive
- **`<details>`** → Expandable content.
- **`<summary>`** → Summary for details.
- **`<dialog>`** → Popup dialog.

---

## ⚡ Scripting
- **`<script>`** → JavaScript code.
- **`<noscript>`** → Content for no-JS.
- **`<canvas>`** → Draw graphics.

---

## 🗑️ Deprecated/Obsolete Tags
(Not recommended, included for history)
- **`<acronym>`** → Use `<abbr>`.
- **`<applet>`** → Old Java applets.
- **`<big>`** → Enlarged text.
- **`<center>`** → Center text.
- **`<dir>`** → Directory list.
- **`<font>`** → Font styles.
- **`<frame>`** → Frame.
- **`<frameset>`** → Group of frames.
- **`<noframes>`** → Alt content.
- **`<strike>`** → Strikethrough.
- **`<tt>`** → Teletype text.
 -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Complete HTML Tags Reference</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
            background-color: #f5f5f5;
        }
        h1 {
            text-align: center;
            color: #333;
            border-bottom: 2px solid #333;
            padding-bottom: 10px;
        }
        h2 {
            background-color: #333;
            color: white;
            padding: 8px;
            border-radius: 5px;
            margin-top: 30px;
        }
        .tag-container {
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            padding: 20px;
            margin-bottom: 20px;
        }
        .tag {
            font-weight: bold;
            color: #0066cc;
            font-size: 1.2em;
            margin-bottom: 5px;
        }
        .description {
            margin-left: 20px;
            margin-bottom: 15px;
        }
        .example {
            background-color: #f8f8f8;
            border-left: 4px solid #0066cc;
            padding: 10px;
            margin: 10px 0;
            font-family: monospace;
            white-space: pre-wrap;
        }
        footer {
            text-align: center;
            margin-top: 40px;
            padding: 20px;
            border-top: 1px solid #ccc;
            color: #666;
        }
    </style>
</head>
<body>
    <h1>Complete HTML Tags Reference</h1>
    <p>This document explains all HTML tags with simple descriptions and examples.</p>

    <h2>Basic Structure Tags</h2>
    <div class="tag-container">
        <div class="tag">&lt;!DOCTYPE&gt;</div>
        <div class="description">Defines the document type and version of HTML. It helps browsers display web pages correctly.</div>
        <div class="example">&lt;!DOCTYPE html&gt;  // Tells the browser this is an HTML5 document</div>

        <div class="tag">&lt;html&gt;</div>
        <div class="description">The root element of an HTML page that contains all other HTML elements.</div>
        <div class="example">&lt;html lang="en"&gt;...&lt;/html&gt;  // Wraps all content on the page</div>

        <div class="tag">&lt;head&gt;</div>
        <div class="description">Contains meta information about the document, like its title, styles, and scripts.</div>
        <div class="example">&lt;head&gt;&lt;title&gt;My Page&lt;/title&gt;&lt;/head&gt;  // Contains page info</div>

        <div class="tag">&lt;title&gt;</div>
        <div class="description">Sets the title of the web page, which appears in the browser's title bar or tab.</div>
        <div class="example">&lt;title&gt;My Website&lt;/title&gt;  // Shows in browser tab</div>

        <div class="tag">&lt;body&gt;</div>
        <div class="description">Contains all the visible content of the web page, like text, images, and links.</div>
        <div class="example">&lt;body&gt;All visible content goes here&lt;/body&gt;  // Main content area</div>
    </div>

    <h2>Metadata Tags</h2>
    <div class="tag-container">
        <div class="tag">&lt;base&gt;</div>
        <div class="description">Specifies a base URL for all relative URLs in a document.</div>
        <div class="example">&lt;base href="https://example.com/"&gt;  // Sets default link location</div>

        <div class="tag">&lt;link&gt;</div>
        <div class="description">Links external resources like CSS files to the HTML document.</div>
        <div class="example">&lt;link rel="stylesheet" href="styles.css"&gt;  // Connects CSS file</div>

        <div class="tag">&lt;meta&gt;</div>
        <div class="description">Provides metadata about the HTML document, like character set or viewport settings.</div>
        <div class="example">&lt;meta charset="UTF-8"&gt;  // Sets character encoding</div>

        <div class="tag">&lt;style&gt;</div>
        <div class="description">Contains CSS code for styling the HTML document.</div>
        <div class="example">&lt;style&gt;body { color: red; }&lt;/style&gt;  // Adds internal CSS</div>
    </div>

    <h2>Sectioning Tags</h2>
    <div class="tag-container">
        <div class="tag">&lt;address&gt;</div>
        <div class="description">Provides contact information for the author or owner of a document.</div>
        <div class="example">&lt;address&gt;Contact us at example@email.com&lt;/address&gt;</div>

        <div class="tag">&lt;article&gt;</div>
        <div class="description">Represents a self-contained composition like a blog post or news story.</div>
        <div class="example">&lt;article&gt;A news story goes here&lt;/article&gt;</div>

        <div class="tag">&lt;aside&gt;</div>
        <div class="description">Contains content that is tangentially related to the main content.</div>
        <div class="example">&lt;aside&gt;This is a sidebar with related info&lt;/aside&gt;</div>

        <div class="tag">&lt;footer&gt;</div>
        <div class="description">Defines a footer for a document or section, typically with copyright info.</div>
        <div class="example">&lt;footer&gt;Copyright 2023&lt;/footer&gt;  // Page footer</div>

        <div class="tag">&lt;header&gt;</div>
        <div class="description">Represents introductory content, typically a group of navigational aids.</div>
        <div class="example">&lt;header&gt;&lt;h1&gt;Website Title&lt;/h1&gt;&lt;/header&gt;</div>

        <div class="tag">&lt;h1&gt; to &lt;h6&gt;</div>
        <div class="description">Defines HTML headings, with h1 being the most important and h6 the least.</div>
        <div class="example">&lt;h1&gt;Main Heading&lt;/h1&gt;  // Largest heading</div>

        <div class="tag">&lt;hgroup&gt;</div>
        <div class="description">Groups a set of h1-h6 elements when a heading has multiple levels.</div>
        <div class="example">&lt;hgroup&gt;&lt;h1&gt;Main&lt;/h1&gt;&lt;h2&gt;Subtitle&lt;/h2&gt;&lt;/hgroup&gt;</div>

        <div class="tag">&lt;main&gt;</div>
        <div class="description">Specifies the main content of a document, which should be unique to that document.</div>
        <div class="example">&lt;main&gt;The primary content of the page&lt;/main&gt;</div>

        <div class="tag">&lt;nav&gt;</div>
        <div class="description">Defines a section of navigation links.</div>
        <div class="example">&lt;nav&gt;&lt;a href="/home"&gt;Home&lt;/a&gt;&lt;/nav&gt;  // Navigation menu</div>

        <div class="tag">&lt;section&gt;</div>
        <div class="description">Defines a section in a document, like chapters or parts of content.</div>
        <div class="example">&lt;section&gt;A chapter of content&lt;/section&gt;</div>
    </div>

    <h2>Grouping Content Tags</h2>
    <div class="tag-container">
        <div class="tag">&lt;div&gt;</div>
        <div class="description">A generic container for flow content, used for grouping and styling.</div>
        <div class="example">&lt;div&gt;A division or section&lt;/div&gt;  // Content container</div>

        <div class="tag">&lt;p&gt;</div>
        <div class="description">Defines a paragraph of text.</div>
        <div class="example">&lt;p&gt;This is a paragraph of text.&lt;/p&gt;</div>

        <div class="tag">&lt;hr&gt;</div>
        <div class="description">Represents a thematic break between paragraph-level elements.</div>
        <div class="example">&lt;hr&gt;  // Creates a horizontal line</div>

        <div class="tag">&lt;pre&gt;</div>
        <div class="description">Defines preformatted text that preserves spaces and line breaks.</div>
        <div class="example">&lt;pre&gt;Text with   spaces and
line breaks preserved&lt;/pre&gt;</div>

        <div class="tag">&lt;blockquote&gt;</div>
        <div class="description">Indicates that the enclosed text is an extended quotation.</div>
        <div class="example">&lt;blockquote&gt;A long quotation from another source&lt;/blockquote&gt;</div>

        <div class="tag">&lt;ol&gt;</div>
        <div class="description">Defines an ordered (numbered) list.</div>
        <div class="example">&lt;ol&gt;&lt;li&gt;First item&lt;/li&gt;&lt;/ol&gt;  // Numbered list</div>

        <div class="tag">&lt;ul&gt;</div>
        <div class="description">Defines an unordered (bulleted) list.</div>
        <div class="example">&lt;ul&gt;&lt;li&gt;List item&lt;/li&gt;&lt;/ul&gt;  // Bullet list</div>

        <div class="tag">&lt;li&gt;</div>
        <div class="description">Defines a list item within ordered or unordered lists.</div>
        <div class="example">&lt;li&gt;An item in a list&lt;/li&gt;</div>

        <div class="tag">&lt;dl&gt;</div>
        <div class="description">Defines a description list (formerly definition list).</div>
        <div class="example">&lt;dl&gt;&lt;dt&gt;Term&lt;/dt&gt;&lt;dd&gt;Description&lt;/dd&gt;&lt;/dl&gt;</div>

        <div class="tag">&lt;dt&gt;</div>
        <div class="description">Defines a term in a description list.</div>
        <div class="example">&lt;dt&gt;HTML&lt;/dt&gt;  // Term to be defined</div>

        <div class="tag">&lt;dd&gt;</div>
        <div class="description">Provides the definition/description of a term in a description list.</div>
        <div class="example">&lt;dd&gt;HyperText Markup Language&lt;/dd&gt;  // Definition</div>

        <div class="tag">&lt;figure&gt;</div>
        <div class="description">Represents self-contained content, like images or diagrams.</div>
        <div class="example">&lt;figure&gt;&lt;img src="image.jpg"&gt;&lt;/figure&gt;</div>

        <div class="tag">&lt;figcaption&gt;</div>
        <div class="description">Defines a caption for a &lt;figure&gt; element.</div>
        <div class="example">&lt;figcaption&gt;Caption for the figure&lt;/figcaption&gt;</div>
    </div>

    <h2>Text-level Semantics Tags</h2>
    <div class="tag-container">
        <div class="tag">&lt;a&gt;</div>
        <div class="description">Defines a hyperlink to another web page or resource.</div>
        <div class="example">&lt;a href="https://example.com"&gt;Click here&lt;/a&gt;  // Link</div>

        <div class="tag">&lt;abbr&gt;</div>
        <div class="description">Defines an abbreviation or acronym, with optional full explanation.</div>
        <div class="example">&lt;abbr title="World Health Organization"&gt;WHO&lt;/abbr&gt;</div>

        <div class="tag">&lt;b&gt;</div>
        <div class="description">Makes text bold without conveying extra importance.</div>
        <div class="example">&lt;b&gt;This text is bold&lt;/b&gt;</div>

        <div class="tag">&lt;bdi&gt;</div>
        <div class="description">Isolates a part of text that might be formatted in a different direction.</div>
        <div class="example">&lt;bdi&gt;Text with different directionality&lt;/bdi&gt;</div>

        <div class="tag">&lt;bdo&gt;</div>
        <div class="description">Overrides the current text direction.</div>
        <div class="example">&lt;bdo dir="rtl"&gt;This text is right-to-left&lt;/bdo&gt;</div>

        <div class="tag">&lt;br&gt;</div>
        <div class="description">Produces a line break in text (carriage-return).</div>
        <div class="example">Line one&lt;br&gt;Line two  // Line break</div>

        <div class="tag">&lt;cite&gt;</div>
        <div class="description">Defines the title of a creative work (e.g., a book, poem, song).</div>
        <div class="example">&lt;cite&gt;The Great Gatsby&lt;/cite&gt; by F. Scott Fitzgerald</div>

        <div class="tag">&lt;code&gt;</div>
        <div class="description">Displays a piece of computer code in monospace font.</div>
        <div class="example">&lt;code&gt;console.log('Hello');&lt;/code&gt;  // Code snippet</div>

        <div class="tag">&lt;data&gt;</div>
        <div class="description">Links content with a machine-readable translation.</div>
        <div class="example">&lt;data value="123"&gt;Product Name&lt;/data&gt;</div>

        <div class="tag">&lt;dfn&gt;</div>
        <div class="description">Represents the defining instance of a term.</div>
        <div class="example">&lt;dfn&gt;HTML&lt;/dfn&gt; is the standard markup language.</div>

        <div class="tag">&lt;em&gt;</div>
        <div class="description">Marks text that has stress emphasis, typically displayed as italic.</div>
        <div class="example">I &lt;em&gt;really&lt;/em&gt; mean it.  // Emphasized text</div>

        <div class="tag">&lt;i&gt;</div>
        <div class="description">Represents text in an alternate voice or mood, typically italic.</div>
        <div class="example">&lt;i&gt;This is italic text&lt;/i&gt;</div>

        <div class="tag">&lt;kbd&gt;</div>
        <div class="description">Represents user keyboard input, shown in monospace font.</div>
        <div class="example">Press &lt;kbd&gt;Ctrl&lt;/kbd&gt; + &lt;kbd&gt;C&lt;/kbd&gt; to copy.</div>

        <div class="tag">&lt;mark&gt;</div>
        <div class="description">Represents text highlighted for reference purposes.</div>
        <div class="example">This is &lt;mark&gt;important text&lt;/mark&gt; to notice.</div>

        <div class="tag">&lt;q&gt;</div>
        <div class="description">Defines a short inline quotation.</div>
        <div class="example">She said, &lt;q&gt;Hello there!&lt;/q&gt;</div>

        <div class="tag">&lt;rp&gt;</div>
        <div class="description">Provides fall-back parentheses for browsers that don't support ruby annotations.</div>
        <div class="example">&lt;ruby&gt;漢 &lt;rp&gt;(&lt;/rp&gt;&lt;rt&gt;kan&lt;/rt&gt;&lt;rp&gt;)&lt;/rp&gt;&lt;/ruby&gt;</div>

        <div class="tag">&lt;rt&gt;</div>
        <div class="description">Defines the pronunciation of character presented in a ruby annotation.</div>
        <div class="example">&lt;ruby&gt;漢 &lt;rt&gt;kan&lt;/rt&gt;&lt;/ruby&gt;</div>

        <div class="tag">&lt;ruby&gt;</div>
        <div class="description">Represents small annotations for showing pronunciation of East Asian characters.</div>
        <div class="example">&lt;ruby&gt;漢 &lt;rt&gt;kan&lt;/rt&gt;&lt;/ruby&gt;</div>

        <div class="tag">&lt;s&gt;</div>
        <div class="description">Renders text with a strikethrough, indicating it's no longer accurate.</div>
        <div class="example">&lt;s&gt;This text is no longer correct&lt;/s&gt;</div>

        <div class="tag">&lt;samp&gt;</div>
        <div class="description">Represents sample output from a computer program.</div>
        <div class="example">&lt;samp&gt;File not found.&lt;/samp&gt;  // Sample output</div>

        <div class="tag">&lt;small&gt;</div>
        <div class="description">Renders side-comments and small print, like copyright text.</div>
        <div class="example">&lt;small&gt;Copyright 2023&lt;/small&gt;  // Small text</div>

        <div class="tag">&lt;span&gt;</div>
        <div class="description">A generic inline container for phrasing content.</div>
        <div class="example">&lt;span style="color:red"&gt;Red text&lt;/span&gt;  // Inline container</div>

        <div class="tag">&lt;strong&gt;</div>
        <div class="description">Indicates strong importance, seriousness, or urgency, typically bold.</div>
        <div class="example">&lt;strong&gt;Warning!&lt;/strong&gt; This is important.</div>

        <div class="tag">&lt;sub&gt;</div>
        <div class="description">Defines subscript text, which appears half a character below the normal line.</div>
        <div class="example">H&lt;sub&gt;2&lt;/sub&gt;O  // Subscript text</div>

        <div class="tag">&lt;sup&gt;</div>
        <div class="description">Defines superscript text, which appears half a character above the normal line.</div>
        <div class="example">E = mc&lt;sup&gt;2&lt;/sup&gt;  // Superscript text</div>

        <div class="tag">&lt;time&gt;</div>
        <div class="description">Represents a specific period in time, can be machine-readable.</div>
        <div class="example">&lt;time datetime="2023-12-25"&gt;Christmas&lt;/time&gt;</div>

        <div class="tag">&lt;u&gt;</div>
        <div class="description">Renders text with an underline, often indicating misspelled text.</div>
        <div class="example">&lt;u&gt;This text is underlined&lt;/u&gt;</div>

        <div class="tag">&lt;var&gt;</div>
        <div class="description">Represents a variable in a mathematical expression or programming context.</div>
        <div class="example">The variable &lt;var&gt;x&lt;/var&gt; represents the unknown value.</div>

        <div class="tag">&lt;wbr&gt;</div>
        <div class="description">Represents a word break opportunity—a position within text where the browser may break a line.</div>
        <div class="example">VeryLongWord&lt;wbr&gt;BreakOpportunity</div>
    </div>

    <h2>Edits Tags</h2>
    <div class="tag-container">
        <div class="tag">&lt;del&gt;</div>
        <div class="description">Represents text that has been deleted from a document, typically shown with strikethrough.</div>
        <div class="example">&lt;del&gt;This text has been deleted&lt;/del&gt;</div>

        <div class="tag">&lt;ins&gt;</div>
        <div class="description">Represents text that has been inserted into a document, typically shown with underline.</div>
        <div class="example">&lt;ins&gt;This text has been inserted&lt;/ins&gt;</div>
    </div>

    <h2>Embedded Content Tags</h2>
    <div class="tag-container">
        <div class="tag">&lt;area&gt;</div>
        <div class="description">Defines a clickable area inside an image map.</div>
        <div class="example">&lt;area shape="rect" coords="0,0,50,50" href="link.html"&gt;</div>

        <div class="tag">&lt;audio&gt;</div>
        <div class="description">Embeds sound content in a document.</div>
        <div class="example">&lt;audio controls&gt;&lt;source src="audio.mp3"&gt;&lt;/audio&gt;</div>

        <div class="tag">&lt;img&gt;</div>
        <div class="description">Embeds an image into the document.</div>
        <div class="example">&lt;img src="image.jpg" alt="Description"&gt;  // Image</div>

        <div class="tag">&lt;map&gt;</div>
        <div class="description">Defines an image map with clickable areas.</div>
        <div class="example">&lt;map name="workmap"&gt;&lt;area shape="rect" coords="0,0,50,50"&gt;&lt;/map&gt;</div>

        <div class="tag">&lt;track&gt;</div>
        <div class="description">Specifies text tracks for media elements like &lt;video&gt; or &lt;audio&gt;.</div>
        <div class="example">&lt;track src="subtitles.vtt" kind="subtitles" srclang="en"&gt;</div>

        <div class="tag">&lt;video&gt;</div>
        <div class="description">Embeds a video player in the document.</div>
        <div class="example">&lt;video controls&gt;&lt;source src="movie.mp4"&gt;&lt;/video&gt;</div>
    </div>

    <h2>SVG and MathML Tags</h2>
    <div class="tag-container">
        <div class="tag">&lt;svg&gt;</div>
        <div class="description">Container for SVG (Scalable Vector Graphics) content.</div>
        <div class="example">&lt;svg width="100" height="100"&gt;&lt;circle cx="50" cy="50" r="40"&gt;&lt;/svg&gt;</div>

        <div class="tag">&lt;math&gt;</div>
        <div class="description">Container for MathML content for mathematical equations.</div>
        <div class="example">&lt;math&gt;&lt;mi&gt;x&lt;/mi&gt;&lt;mo&gt;+&lt;/mo&gt;&lt;mi&gt;y&lt;/mi&gt;&lt;/math&gt;</div>
    </div>

    <h2>Table Content Tags</h2>
    <div class="tag-container">
        <div class="tag">&lt;table&gt;</div>
        <div class="description">Defines a table for displaying data in rows and columns.</div>
        <div class="example">&lt;table&gt;&lt;tr&gt;&lt;td&gt;Cell&lt;/td&gt;&lt;/tr&gt;&lt;/table&gt;</div>

        <div class="tag">&lt;caption&gt;</div>
        <div class="description">Defines a table caption, which describes the table.</div>
        <div class="example">&lt;caption&gt;Monthly Sales&lt;/caption&gt;  // Table title</div>

        <div class="tag">&lt;colgroup&gt;</div>
        <div class="description">Specifies a group of one or more columns in a table for formatting.</div>
        <div class="example">&lt;colgroup&gt;&lt;col span="2" style="background-color:red"&gt;&lt;/colgroup&gt;</div>

        <div class="tag">&lt;col&gt;</div>
        <div class="description">Specifies column properties for each column within a &lt;colgroup&gt;.</div>
        <div class="example">&lt;col style="width:50%"&gt;  // Column properties</div>

        <div class="tag">&lt;tbody&gt;</div>
        <div class="description">Groups the body content in a table.</div>
        <div class="example">&lt;tbody&gt;&lt;tr&gt;&lt;td&gt;Data&lt;/td&gt;&lt;/tr&gt;&lt;/tbody&gt;</div>

        <div class="tag">&lt;thead&gt;</div>
        <div class="description">Groups the header content in a table.</div>
        <div class="example">&lt;thead&gt;&lt;tr&gt;&lt;th&gt;Header&lt;/th&gt;&lt;/tr&gt;&lt;/thead&gt;</div>

        <div class="tag">&lt;tfoot&gt;</div>
        <div class="description">Groups the footer content in a table.</div>
        <div class="example">&lt;tfoot&gt;&lt;tr&gt;&lt;td&gt;Total&lt;/td&gt;&lt;/tr&gt;&lt;/tfoot&gt;</div>

        <div class="tag">&lt;tr&gt;</div>
        <div class="description">Defines a row in a table.</div>
        <div class="example">&lt;tr&gt;&lt;td&gt;Cell 1&lt;/td&gt;&lt;td&gt;Cell 2&lt;/td&gt;&lt;/tr&gt;</div>

        <div class="tag">&lt;td&gt;</div>
        <div class="description">Defines a standard data cell in a table.</div>
        <div class="example">&lt;td&gt;Table cell data&lt;/td&gt;</div>

        <div class="tag">&lt;th&gt;</div>
        <div class="description">Defines a header cell in a table.</div>
        <div class="example">&lt;th&gt;Column Header&lt;/th&gt;  // Table header</div>
    </div>

    <h2>Forms Tags</h2>
    <div class="tag-container">
        <div class="tag">&lt;form&gt;</div>
        <div class="description">Creates an HTML form for user input.</div>
        <div class="example">&lt;form action="/submit" method="post"&gt;Form elements&lt;/form&gt;</div>

        <div class="tag">&lt;fieldset&gt;</div>
        <div class="description">Groups related elements in a form with a box around them.</div>
        <div class="example">&lt;fieldset&gt;&lt;legend&gt;Personal Info&lt;/legend&gt;...&lt;/fieldset&gt;</div>

        <div class="tag">&lt;legend&gt;</div>
        <div class="description">Defines a caption for a &lt;fieldset&gt; element.</div>
        <div class="example">&lt;legend&gt;Personal Information&lt;/legend&gt;  // Fieldset title</div>

        <div class="tag">&lt;label&gt;</div>
        <div class="description">Defines a label for an &lt;input&gt; element, improving accessibility.</div>
        <div class="example">&lt;label for="name"&gt;Name:&lt;/label&gt;  // Input label</div>

        <div class="tag">&lt;input&gt;</div>
        <div class="description">Creates an input field where users can enter data, with various types.</div>
        <div class="example">&lt;input type="text" name="username"&gt;  // Text input</div>

        <div class="tag">&lt;button&gt;</div>
        <div class="description">Creates a clickable button that can submit forms or trigger actions.</div>
        <div class="example">&lt;button type="submit"&gt;Submit&lt;/button&gt;  // Clickable button</div>

        <div class="tag">&lt;select&gt;</div>
        <div class="description">Creates a drop-down list of options for users to choose from.</div>
        <div class="example">&lt;select&gt;&lt;option value="1"&gt;Option 1&lt;/option&gt;&lt;/select&gt;</div>

        <div class="tag">&lt;datalist&gt;</div>
        <div class="description">Specifies a list of pre-defined options for an &lt;input&gt; element.</div>
        <div class="example">&lt;datalist id="browsers"&gt;&lt;option value="Chrome"&gt;&lt;/datalist&gt;</div>

        <div class="tag">&lt;optgroup&gt;</div>
        <div class="description">Groups related options in a drop-down list.</div>
        <div class="example">&lt;optgroup label="Group Name"&gt;&lt;option&gt;Option&lt;/option&gt;&lt;/optgroup&gt;</div>

        <div class="tag">&lt;option&gt;</div>
        <div class="description">Defines an option in a drop-down list within &lt;select&gt; or &lt;datalist&gt;.</div>
        <div class="example">&lt;option value="value"&gt;Display Text&lt;/option&gt;</div>

        <div class="tag">&lt;textarea&gt;</div>
        <div class="description">Defines a multi-line text input control for longer text entries.</div>
        <div class="example">&lt;textarea rows="4" cols="50"&gt;Default text&lt;/textarea&gt;</div>

        <div class="tag">&lt;output&gt;</div>
        <div class="description">Represents the result of a calculation or user action.</div>
        <div class="example">&lt;output name="result"&gt;0&lt;/output&gt;  // Calculation result</div>

        <div class="tag">&lt;progress&gt;</div>
        <div class="description">Represents the completion progress of a task, typically displayed as a progress bar.</div>
        <div class="example">&lt;progress value="70" max="100"&gt;70%&lt;/progress&gt;</div>

        <div class="tag">&lt;meter&gt;</div>
        <div class="description">Represents a scalar measurement within a known range, or a fractional value.</div>
        <div class="example">&lt;meter value="0.6"&gt;60%&lt;/meter&gt;  // Measurement gauge</div>
    </div>

    <h2>Interactive Elements Tags</h2>
    <div class="tag-container">
        <div class="tag">&lt;details&gt;</div>
        <div class="description">Creates a disclosure widget where information is visible only when toggled open.</div>
        <div class="example">&lt;details&gt;&lt;summary&gt;More Info&lt;/summary&gt;Content&lt;/details&gt;</div>

        <div class="tag">&lt;summary&gt;</div>
        <div class="description">Specifies a visible heading for a &lt;details&gt; element that can be clicked to toggle.</div>
        <div class="example">&lt;summary&gt;Click to expand&lt;/summary&gt;  // Details heading</div>

        <div class="tag">&lt;dialog&gt;</div>
        <div class="description">Defines a dialog box or window that can be shown or hidden.</div>
        <div class="example">&lt;dialog open&gt;This is a dialog box&lt;/dialog&gt;</div>
    </div>

    <h2>Scripting Tags</h2>
    <div class="tag-container">
        <div class="tag">&lt;script&gt;</div>
        <div class="description">Embeds or references executable code, typically JavaScript.</div>
        <div class="example">&lt;script&gt;alert('Hello!');&lt;/script&gt;  // JavaScript code</div>

        <div class="tag">&lt;noscript&gt;</div>
        <div class="description">Defines content to be displayed if scripts are not supported or disabled.</div>
        <div class="example">&lt;noscript&gt;Your browser doesn't support JavaScript&lt;/noscript&gt;</div>

        <div class="tag">&lt;canvas&gt;</div>
        <div class="description">Used to draw graphics via scripting (usually JavaScript).</div>
        <div class="example">&lt;canvas id="myCanvas" width="200" height="100"&gt;&lt;/canvas&gt;</div>
    </div>

    <h2>Deprecated Tags (Avoid Using)</h2>
    <div class="tag-container">
        <div class="tag">&lt;acronym&gt;</div>
        <div class="description">Deprecated. Was used for acronyms. Use &lt;abbr&gt; instead.</div>

        <div class="tag">&lt;applet&gt;</div>
        <div class="description">Deprecated. Was used to embed Java applets. Use &lt;embed&gt; or &lt;object&gt; instead.</div>

        <div class="tag">&lt;big&gt;</div>
        <div class="description">Deprecated. Was used to make text bigger. Use CSS instead.</div>

        <div class="tag">&lt;center&gt;</div>
        <div class="description">Deprecated. Was used to center content. Use CSS instead.</div>

        <div class="tag">&lt;dir&gt;</div>
        <div class="description">Deprecated. Was used for directory lists. Use &lt;ul&gt; instead.</div>

        <div class="tag">&lt;font&gt;</div>
        <div class="description">Deprecated. Was used for font styling. Use CSS instead.</div>

        <div class="tag">&lt;frame&gt;</div>
        <div class="description">Deprecated. Was used to define a particular window (frame) within a &lt;frameset&gt;.</div>

        <div class="tag">&lt;frameset&gt;</div>
        <div class="description">Deprecated. Was used to define a set of frames for a page layout.</div>

        <div class="tag">&lt;noframes&gt;</div>
        <div class="description">Deprecated. Was used to provide content for browsers that don't support frames.</div>

        <div class="tag">&lt;strike&gt;</div>
        <div class="description">Deprecated. Was used for strikethrough text. Use &lt;del&gt; or CSS instead.</div>

        <div class="tag">&lt;tt&gt;</div>
        <div class="description">Deprecated. Was used for teletype text. Use &lt;code&gt; or CSS instead.</div>
    </div>

    <footer>
        <p>HTML Tags Reference Guide - Created for educational purposes</p>
        <p>Note: Some tags are deprecated and should not be used in new projects.</p>
    </footer>
</body>
</html>