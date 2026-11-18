# HTML Elements Supported by React


| HTML ELEMENT | DESCRIPTION | EXAMPLE USAGE |
| :--- | :--- | :--- |
| `a` | Creates a hyperlink. | `<a href="https://react.dev">React Docs</a>` |
| `abbr` | Represents an abbreviation or acronym. | `<abbr title="HyperText Markup Language">HTML</abbr>` |
| `address` | Indicates that the containing HTML includes contact information. | `<address>123 React Way, Web City</address>` |
| `area` | Defines a clickable area in an image map. | `<area shape="rect" coords="34,44,270,350" href="page.html" alt="Area" />` |
| `article` | Represents a self-contained composition (such as a story or an article) in a page. | `<article><h2>News Title</h2><p>Content...</p></article>` |
| `aside` | Represents content that is indirectly related to the main content. | `<aside><p>Related sidebar note</p></aside>` |
| `audio` | Embeds sound content. | `<audio controls src="/sound.mp3" />` |
| `b` | Used to draw the reader’s attention to the contents. | `<p>The <b>key</b> takeaway is speed.</p>` |
| `base` | Specifies the base URL for all relative URLs in the document. | `<base href="https://example.com/" />` |
| `bdi` | Bidirectional Isolate. Isolates text that may flow in a different direction from text around it. | `<p>User: <bdi>إيان</bdi></p>` |
| `bdo` | Bidirectional Text Override. Changes the direction of text. | `<bdo dir="rtl">Right to left text</bdo>` |
| `big` | Renders text at a font size one level larger (obsolete). | `<big>Larger text</big>` |
| `blockquote` | Indicates an extended quotation. | `<blockquote cite="https://source.com"><p>Quote text</p></blockquote>` |
| `body` | Represents the content of an HTML document. | `<body><div id="root"></div></body>` |
| `br` | Produces a line break. | `<p>Line one<br />Line two</p>` |
| `button` | Represents a clickable button. | `<button type="button" onClick={handleClick}>Click Me</button>` |
| `canvas` | Creates an area for drawing with the canvas API or WebGL. | `<canvas id="myCanvas" width={200} height={100} />` |
| `caption` | Specifies a caption for a table. | `<table><caption>Monthly Savings</caption></table>` |
| `center` | Centers its block or inline contents horizontally (deprecated). | `<center>Centered content</center>` |
| `cite` | Describes a reference to a cited work. | `<p>More in <cite>The React Handbook</cite>.</p>` |
| `code` | Indicates that its content should be styled as computer code. | `<code>const x = 10;</code>` |
| `col` | Defines a column within a table. | `<col span={2} style={{ backgroundColor: 'gray' }} />` |
| `colgroup` | Defines a group of columns in a table. | `<colgroup><col span={2} /></colgroup>` |
| `data` | Links content to a machine-readable translation. | `<data value="21053">Cherry Tomato</data>` |
| `datalist` | Contains option elements indicating the permissible options available for a form control. | `<datalist id="browsers"><option value="Chrome" /></datalist>` |
| `dd` | Provides the definition for a preceding term (specified using dt). | `<dl><dt>HTML</dt><dd>Markup language</dd></dl>` |
| `del` | Represents text that has been deleted from a document. | `<p>Price: <del>$50</del> $30</p>` |
| `details` | Creates a widget in which information is visible when the widget is toggled to its “open” state. | `<details><summary>More info</summary><p>Hidden details</p></details>` |
| `dfn` | Indicates the term being defined within a sentence. | `<p><dfn>JSX</dfn> is a syntax extension for JavaScript.</p>` |
| `dialog` | Represents a dialog box, subwindow, alert box, or other such interactive element. | `<dialog open><p>Alert message!</p></dialog>` |
| `div` | A generic container with no effect on content or layout. | `<div className="container">Content</div>` |
| `dl` | Represents a description list. | `<dl><dt>Term</dt><dd>Description</dd></dl>` |
| `dt` | Specifies a term in a definition list. Used inside dl. | `<dt>Component</dt>` |
| `em` | Marks text that has emphasis. | `<p>You <em>must</em> save your work.</p>` |
| `embed` | Embeds external content in the document. | `<embed type="video/webm" src="/video.webm" width={250} />` |
| `fieldset` | Groups controls and labels within a form. | `<fieldset><legend>Profile</legend><input /></fieldset>` |
| `figcaption` | Describes the contents of a parent figure element. | `<figure><img src="pic.jpg" alt="Pic" /><figcaption>Fig 1.</figcaption></figure>` |
| `figure` | Represents self-contained content, optionally with a caption. | `<figure><img src="chart.png" alt="Chart" /></figure>` |
| `footer` | Represents a footer for its nearest sectioning content. | `<footer>© 2026 My App</footer>` |
| `form` | Represents a document section containing interactive controls. | `<form onSubmit={handleSubmit}><button type="submit">Send</button></form>` |
| `h1` | First-level section heading. | `<h1>Main Page Title</h1>` |
| `h2` | Second-level section heading. | `<h2>Section Heading</h2>` |
| `h3` | Third-level section heading. | `<h3>Subsection Heading</h3>` |
| `h4` | Fourth-level section heading. | `<h4>Sub-subsection Heading</h4>` |
| `h5` | Fifth-level section heading. | `<h5>Minor Heading</h5>` |
| `h6` | Sixth-level section heading. | `<h6>Smallest Heading</h6>` |
| `head` | Contains machine-readable information about the document. | `<head><title>App</title></head>` |
| `header` | Represents introductory content. | `<header><h1>Welcome</h1></header>` |
| `hgroup` | Represents a heading and related content (such as a subtitle). | `<hgroup><h1>Title</h1><p>Subtitle</p></hgroup>` |
| `hr` | Represents a thematic break between sections. | `<p>Section 1</p><hr /><p>Section 2</p>` |
| `html` | Represents the root of an HTML document. | `<html lang="en"><body>...</body></html>` |
| `i` | Represents idiomatic text that is set off from the normal text. | `<p>The ship <i>Titanic</i> sank in 1912.</p>` |
| `iframe` | Represents a nested browser context. | `<iframe src="https://example.com" title="Embed" />` |
| `img` | Embeds an image into the document. | `<img src="/logo.png" alt="App Logo" />` |
| `input` | Creates interactive controls for web-based forms. | `<input type="text" placeholder="Enter name" />` |
| `ins` | Represents a range of text that has been added to the document. | `<p>Updated status: <ins>Approved</ins></p>` |
| `kbd` | Represents a span of text denoting textual user input. | `<p>Press <kbd>Ctrl</kbd> + <kbd>S</kbd> to save.</p>` |
| `keygen` | Facilitates generation of key material and submission of the public key in an HTML form. | `<keygen name="rsaPublicKey" />` |
| `label` | Represents a caption for an item in a user interface. | `<label htmlFor="email">Email:</label>` |
| `legend` | Represents a caption for an element in a fieldset. | `<fieldset><legend>Personal Info</legend></fieldset>` |
| `li` | Represents an item in a list. | `<ul><li>First item</li></ul>` |
| `link` | Specifies a relationship between the document and an external resource. Commonly used to link stylesheets. | `<link rel="stylesheet" href="/styles.css" />` |
| `main` | Represents the dominant content of the body of a document. | `<main><h1>Dashboard</h1></main>` |
| `map` | Used with area elements to define an imagemap. | `<map name="workmap"><area shape="rect" coords="0,0,50,50" href="#" alt="Link" /></map>` |
| `mark` | Represents marked, or highlighted, text. | `<p>Search result: <mark>React</mark></p>` |
| `menu` | Represents a group of commands. | `<menu><li><button>Copy</button></li></menu>` |
| `menuitem` | Represents a command in a menu. | `<menuitem label="Refresh" onClick={refresh} />` |
| `meta` | Represents metadata that can’t be represented with other metadata elements (such as title, link, script, or style). | `<meta name="viewport" content="width=device-width" />` |
| `meter` | Represents a fractional value or a scalar value within a known range. | `<meter value={0.6}>60%</meter>` |
| `nav` | Represents a section containing navigation links. | `<nav><a href="/home">Home</a></nav>` |
| `noindex` | Non-standard element used to prevent search engines from indexing specific content. | `<noindex><p>Do not index this block</p></noindex>` |
| `noscript` | Represents a section to be inserted if a script type is unsupported or if scripting is disabled in the browser. | `<noscript>Please enable JavaScript.</noscript>` |
| `object` | Represents an external resource. | `<object data="/file.pdf" type="application/pdf" />` |
| `ol` | Represents an ordered list. | `<ol><li>Step 1</li><li>Step 2</li></ol>` |
| `optgroup` | Creates a grouping of options within a select element. | `<select><optgroup label="Group 1"><option>A</option></optgroup></select>` |
| `option` | Defines an item in a select or optgroup. | `<option value="react">React</option>` |
| `output` | Creates a container for the results of a calculation or for user input. | `<output name="result">42</output>` |
| `p` | Represents a paragraph. | `<p>This is a paragraph of text.</p>` |
| `param` | Defines parameters for an object. | `<object data="movie.swf"><param name="autoplay" value="true" /></object>` |
| `picture` | Contains source elements and an img element to provide alternative versions of an image. | `<picture><source srcSet="img.webp" /><img src="img.jpg" alt="" /></picture>` |
| `pre` | Represents preformatted text which should be presented exactly as written. | `<pre>{JSON.stringify(data, null, 2)}</pre>` |
| `progress` | Displays an indicator showing progress towards the completion of a task, such as a progress bar. | `<progress value={70} max={100}>70%</progress>` |
| `q` | Indicates that its content is a quotation. | `<p>She said, <q>Keep it simple.</q></p>` |
| `rp` | Used to provide fallback content for browsers that don’t support ruby annotations using the ruby element. | `<ruby>漢<rp>(</rp><rt>Kan</rt><rp>)</rp></ruby>` |
| `rt` | Specifies the ruby text component of a ruby annotation. | `<ruby>漢<rt>Kan</rt></ruby>` |
| `ruby` | Represents annotations for showing the pronunciation of East Asian characters. | `<ruby>明日 <rt>Ashita</rt></ruby>` |
| `s` | Represents a strikethrough. | `<p><s>Old price: $100</s></p>` |
| `samp` | Encloses text that represents sample output from a computer program. | `<p>Output: <samp>Build succeeded.</samp></p>` |
| `script` | Embeds executable code or data. | `<script src="/analytics.js" async />` |
| `search` | Represents a part of the document containing controls for searching or filtering. | `<search><input type="search" placeholder="Search..." /></search>` |
| `section` | Represents a standalone section in a document. | `<section><h2>Features</h2></section>` |
| `select` | Represents a control that shows a menu of options. | `<select defaultValue="a"><option value="a">A</option></select>` |
| `slot` | A placeholder inside a web component that you can fill with your own markup. | `<slot name="header">Default Header</slot>` |
| `small` | Represents small print, such as copyright or legal text. | `<small>Terms and conditions apply.</small>` |
| `source` | Specifies multiple media resources for picture and audio elements. | `<audio controls><source src="audio.ogg" type="audio/ogg" /></audio>` |
| `span` | A generic inline container. | `<span className="badge">New</span>` |
| `strong` | Indicates that its contents have strong importance. | `<p><strong>Warning:</strong> Do not delete.</p>` |
| `style` | Contains style information for a document. | `<style>{`.box { color: red; }`}</style>` |
| `sub` | Specifies inline text that should be displayed as subscript. | `<p>H<sub>2</sub>O</p>` |
| `summary` | Specifies a summary, legend, or caption for details content. | `<details><summary>Click to expand</summary></details>` |
| `sup` | Specifies inline text that should be displayed as superscript. | `<p>E = mc<sup>2</sup></p>` |
| `table` | Represents tabular data. | `<table><tbody><tr><td>Cell</td></tr></tbody></table>` |
| `tbody` | Encapsulates table rows in a table. | `<tbody><tr><td>Row 1</td></tr></tbody>` |
| `td` | Defines a cell in a table. | `<tr><td>Data cell</td></tr>` |
| `template` | Holds HTML that is not rendered immediately, instantiated later via JavaScript. | `<template id="row-tpl"><tr><td>Item</td></tr></template>` |
| `textarea` | Represents a multi-line text editing control. | `<textarea rows={4} defaultValue="Notes..." />` |
| `tfoot` | Defines a set of rows summarizing the columns in a table. | `<tfoot><tr><td>Total: $100</td></tr></tfoot>` |
| `th` | Defines a cell as a header of a group of table cells. | `<thead><tr><th>Name</th></tr></thead>` |
| `thead` | Defines a set of rows defining the head of the columns in a table. | `<thead><tr><th>Column Header</th></tr></thead>` |
| `time` | Represents a period of time. | `<time dateTime="2026-11-18">November 18, 2026</time>` |
| `title` | Defines the title that is shown in the browser’s title bar and browser tab. | `<title>My React Sandbox</title>` |
| `tr` | Defines a row of cells in a table. | `<tr><td>Cell 1</td><td>Cell 2</td></tr>` |
| `track` | Contains timed text tracks (such as subtitles) for audio and video content. | `<video><track kind="subtitles" src="/subs.vtt" srcLang="en" /></video>` |
| `u` | Originally the underline element, specifies text with non-textual annotation. | `<p>This word is <u>spelled</u> wrong.</p>` |
| `ul` | Represents an unordered list (usually rendered as a bulleted list). | `<ul><li>Apple</li><li>Banana</li></ul>` |
| `var` | Represents the name of a variable in mathematic or programming context. | `<p>Solve for <var>x</var>.</p>` |
| `video` | Embeds a media player that supports video playback. | `<video controls src="/movie.mp4" width={400} />` |
| `wbr` | Represents a word break opportunity, where the browser may optionally break a line. | `<p>https://example.com/<wbr />very-long-path</p>` |
| `webview` | Electron/Chrome element used to embed external web content inside an app. | `<webview src="https://react.dev" />` |
