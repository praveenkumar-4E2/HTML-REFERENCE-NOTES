# HTML-REFERENCE-NOTES
**Most used**

- [Document Structure](#document-structure)
- [Text Content](#text-content)
- [Grouping Content](#grouping-content)
- [Lists](#lists)
- [Tables](#tables)
- [Forms](#forms)
- [Media Elements](#media-elements)
- [Links](Links)
- [Scripting](#scripting)
- [Interactive Elements](#interactive-elements)
- [Meta Elements](#meta-elements)

# Attributes
- [Element Attributes](#all-common-attributes-for-each-html-element)
- [Global Attributes](#global-attributes)
- [Attributes with values](#html-attributes-along-with-their-possible-value-types)


## Document Structure
```html
<html>: The root element of an HTML document.
<head>: Contains metadata, title, and links to external resources.
<body>: Contains the main content of the HTML document.
<title>: Defines the title of the document (shown in the browser's title bar or tab).
<meta>: Provides metadata about the document (charset, viewport, etc.).
<link>: Links to external resources like stylesheets.
<style>: Embeds CSS styles within the document.
<script>: Embeds or links to JavaScript code.
```

## Text Content

```html
<h1> to <h6>: Heading levels (h1 is the highest, h6 the lowest).
<p>: Defines a paragraph.
<br>: Inserts a line break.
<hr>: Inserts a horizontal rule (divider).
<pre>: Defines preformatted text.
<blockquote>: Defines a block quotation.
<code>: Represents a block of code.
<b>: Makes text bold (for stylistic purposes).
<strong>: Emphasizes text, usually bold.
<i>: Italicizes text (for stylistic purposes).
<em>: Emphasizes text, usually italic.
<u>: Underlines text.
<mark>: Highlights text.
<small>: Displays smaller text.
<sup>: Superscript text.
<sub>: Subscript text.
<abbr>: Represents an abbreviation.
<cite>: Represents a citation.
<q>: Defines an inline quotation.

```

## Grouping Content

```html
<div>: Generic container for block-level content.
<span>: Generic container for inline content.
<section>: Defines a section in a document.
<article>: Defines an independent piece of content.
<aside>: Defines content aside from the main content.
<header>: Defines a header for a section or page.
<footer>: Defines a footer for a section or page.
<nav>: Defines navigation links.
<main>: Specifies the main content of a document.
<figure>: Groups media elements (like images and captions).
<figcaption>: Defines a caption for a figure element.
```



# Lists
```html
<ul>: Defines an unordered list.
<ol>: Defines an ordered list.
<li>: Defines a list item.
<dl>: Defines a description list.
<dt>: Defines a term in a description list.
<dd>: Defines a description of a term in a description list.
```


# Tables

```html
<table>: Defines a table.
<tr>: Defines a table row.
<td>: Defines a table cell.
<th>: Defines a header cell in a table.
<thead>: Groups the header content in a table.
<tbody>: Groups the body content in a table.
<tfoot>: Groups the footer content in a table.
<caption>: Defines a table caption.
<colgroup>: Groups columns in a table.
<col>: Specifies column properties.
```

# Forms

```html
<form>: Defines an HTML form for user input.
<input>: Defines an input field (text, password, radio, checkbox, etc.).
<textarea>: Defines a multi-line text input.
<button>: Defines a clickable button.
<select>: Defines a dropdown list.
<option>: Defines an option in a dropdown list.
<optgroup>: Groups related options in a dropdown.
<label>: Defines a label for an input element.
<fieldset>: Groups related elements in a form.
<legend>: Defines a caption for a <fieldset>.
<datalist>: Defines a list of pre-defined options for input fields.
<output>: Represents the result of a calculation.
```

# Media Elements
```html
<img>: Embeds an image.
<audio>: Embeds audio content.
<video>: Embeds video content.
<source>: Defines multiple media resources for <audio> and <video>.
<track>: Defines text tracks for <video> and <audio> (such as subtitles).
<embed>: Embeds external content (e.g., a plugin).
<iframe>: Embeds another HTML document inside the current one.
```

# Links
```html
<a>: Defines a hyperlink.
<link>: Defines a relationship between a document and an external resource (mostly used for stylesheets).
```


# Scripting

```html
<script>: Embeds or references JavaScript.
<noscript>: Defines content to display if JavaScript is disabled.
<canvas>: Provides a space for drawing graphics with JavaScript.
```
# Interactive Elements
```html
<details>: Creates an interactive widget that users can open and close.
<summary>: Defines a summary for the <details> element.
<dialog>: Defines a dialog box or modal window.
```

# Meta Elements

```html
<meta>: Defines metadata like character set, author, and viewport.
<base>: Defines the base URL for all relative URLs in a document.
```

<br></br>

```html

<html>
  ├── <head>
  │   ├── <title>
  │   ├── <meta>
  │   ├── <link>
  │   └── <style>
  └── <body>
      ├── <header>
      ├── <nav>
      ├── <main>
      ├── <footer>
      ├── <section>
      ├── <article>
      ├── <aside>
      ├── <blockquote>
      ├── <pre>
      ├── <code>
      ├── <samp>
      ├── <var>
      ├── <small>
      ├── <strong>
      ├── <em>
      ├── <i>
      ├── <b>
      ├── <u>
      ├── <mark>
      ├── <s>
      ├── <del>
      └── <ins>
      ├── <ul>
      │   └── <li>
      ├── <ol>
      │   └── <li>
      ├── <dl>
      │   ├── <dt>
      │   └── <dd>
      ├── <a>
      ├── <menu>
      ├── <form>
      │   ├── <input>
      │   ├── <textarea>
      │   ├── <button>
      │   ├── <select>
      │   │   └── <option>
      │   ├── <fieldset>
      │   ├── <label>
      │   ├── <datalist>
      │   │   └── <option>
      │   └── <output>
      ├── <table>
      │   ├── <thead>
      │   ├── <tbody>
      │   ├── <tfoot>
      │   └── <tr>
      │       ├── <th>
      │       └── <td>
      ├── <audio>
      ├── <video>
      │   ├── <source>
      │   └── <track>
      ├── <img>
      ├── <picture>
      ├── <canvas>
      ├── <iframe>
      ├── <object>
      ├── <embed>
      ├── <script>
      ├── <details>
      │   └── <summary>
      ├── <dialog>
      ├── <slot>
      ├── <template>
      ├── <data>
      ├── <progress>
      ├── <meter>
      └── <time>
      ├── <bdi>
      └── <bdo>
      ├── <portal> (Experimental)
      └── <fencedframe> (Experimental)




```

<br></br>


# All common attributes for each HTML element



```html

<html>
   ├── lang
   ├── xmlns

<head>
   ├── profile

<body>
   ├── alink
   ├── background
   ├── bgcolor
   ├── link
   ├── text
   ├── vlink

<title>
   ├── None

<meta>
   ├── charset
   ├── content
   ├── http-equiv
   ├── name

<link>
   ├── href
   ├── rel
   ├── type
   ├── media
   ├── hreflang
   ├── sizes

<style>
   ├── media
   ├── scoped
   ├── type

<script>
   ├── async
   ├── defer
   ├── src
   ├── type

<h1> to <h6>
   ├── align

<p>
   ├── align

<br>
   ├── None

<hr>
   ├── align
   ├── noshade
   ├── size
   ├── width

<pre>
   ├── None

<blockquote>
   ├── cite

<code>
   ├── None

<b>, <i>, <u>, <small>, <strong>, <em>, <mark>, <sup>, <sub>, <abbr>, <cite>, <q>, <span>
   ├── None

<div>
   ├── align

<section>, <article>, <aside>, <header>, <footer>, <main>, <nav>, <figure>, <figcaption>
   ├── None

<ul>, <ol>
   ├── type
   ├── compact

<li>
   ├── value

<dl>, <dt>, <dd>
   ├── None

<table>
   ├── align
   ├── bgcolor
   ├── border
   ├── cellpadding
   ├── cellspacing
   ├── frame
   ├── rules
   ├── summary
   ├── width

<tr>
   ├── align
   ├── bgcolor
   ├── valign

<td>, <th>
   ├── abbr
   ├── align
   ├── axis
   ├── bgcolor
   ├── colspan
   ├── headers
   ├── rowspan
   ├── valign
   ├── width

<thead>, <tbody>, <tfoot>
   ├── align
   ├── bgcolor
   ├── valign

<caption>
   ├── align

<colgroup>, <col>
   ├── align
   ├── span
   ├── width
   ├── valign

<form>
   ├── accept-charset
   ├── action
   ├── autocomplete
   ├── enctype
   ├── method
   ├── name
   ├── novalidate
   ├── target

<input>
   ├── accept
   ├── alt
   ├── autocomplete
   ├── autofocus
   ├── checked
   ├── dirname
   ├── disabled
   ├── form
   ├── formaction
   ├── formenctype
   ├── formmethod
   ├── formnovalidate
   ├── formtarget
   ├── height
   ├── list
   ├── max
   ├── maxlength
   ├── min
   ├── minlength
   ├── multiple
   ├── name
   ├── pattern
   ├── placeholder
   ├── readonly
   ├── required
   ├── size
   ├── src
   ├── step
   ├── type
   ├── value
   ├── width

<textarea>
   ├── autocomplete
   ├── autofocus
   ├── cols
   ├── dirname
   ├── disabled
   ├── form
   ├── maxlength
   ├── minlength
   ├── name
   ├── placeholder
   ├── readonly
   ├── required
   ├── rows
   ├── wrap

<button>
   ├── autofocus
   ├── disabled
   ├── form
   ├── formaction
   ├── formenctype
   ├── formmethod
   ├── formnovalidate
   ├── formtarget
   ├── name
   ├── type
   ├── value

<select>
   ├── autocomplete
   ├── autofocus
   ├── disabled
   ├── form
   ├── multiple
   ├── name
   ├── required
   ├── size

<option>
   ├── disabled
   ├── label
   ├── selected
   ├── value

<optgroup>
   ├── disabled
   ├── label

<label>
   ├── for
   ├── form

<fieldset>
   ├── disabled
   ├── form
   ├── name

<legend>
   ├── None

<datalist>
   ├── None

<output>
   ├── for
   ├── form
   ├── name

<img>
   ├── alt
   ├── crossorigin
   ├── height
   ├── ismap
   ├── loading
   ├── referrerpolicy
   ├── sizes
   ├── src
   ├── srcset
   ├── width
   ├── usemap

<audio>
   ├── autoplay
   ├── controls
   ├── crossorigin
   ├── loop
   ├── muted
   ├── preload
   ├── src

<video>
   ├── autoplay
   ├── controls
   ├── crossorigin
   ├── height
   ├── loop
   ├── muted
   ├── playsinline
   ├── poster
   ├── preload
   ├── src
   ├── width

<source>
   ├── src
   ├── type
   ├── media
   ├── sizes
   ├── srcset

<track>
   ├── default
   ├── kind
   ├── label
   ├── src
   ├── srclang

<embed>
   ├── height
   ├── src
   ├── type
   ├── width

<iframe>
   ├── allow
   ├── allowfullscreen
   ├── height
   ├── loading
   ├── name
   ├── referrerpolicy
   ├── sandbox
   ├── src
   ├── srcdoc
   ├── width

<a>
   ├── download
   ├── href
   ├── hreflang
   ├── ping
   ├── referrerpolicy
   ├── rel
   ├── target
   ├── type

<canvas>
   ├── height
   ├── width

<noscript>
   ├── None

<details>
   ├── open

<summary>
   ├── None

<dialog>
   ├── open





```









<br></br>



# HTML attributes along with their possible value types

## Global Attributes

```html
Global Attributes
├── accesskey : Defines a keyboard shortcut to activate/focus an element.
├── autocapitalize : Controls the capitalization of text (none, sentences, words, characters).
├── autofocus : Automatically focuses the element when the page loads.
├── class : Assigns one or more class names for CSS styling.
├── contenteditable : Specifies whether the element's content is editable (true, false).
├── contextmenu : Specifies a context menu for an element.
├── data-* : Custom data attributes, where "*" is a user-defined key (e.g., data-id, data-name).
├── dir : Defines the text direction (ltr, rtl).
├── draggable : Specifies whether the element is draggable (true, false, auto).
├── enterkeyhint : Provides a hint for the action label on enter key (e.g., search, send, done).
├── hidden : Hides the element.
├── id : Defines a unique identifier for the element.
├── inert : Makes an element inactive (cannot be interacted with).
├── inputmode : Specifies the type of virtual keyboard (e.g., text, numeric, tel).
├── is : Used to extend built-in elements using Web Components.
├── itemid : Specifies the unique identifier for microdata items.
├── itemprop : Defines properties of a microdata item.
├── itemref : Refers to other properties of a microdata item.
├── itemscope : Indicates that the element creates a microdata item.
├── itemtype : Defines the type of the microdata item (URL).
├── lang : Specifies the language of the element's content.
├── nonce : Used to allow trusted inline scripts by providing a cryptographic nonce.
├── role : Defines the role for accessibility (e.g., button, navigation).
├── slot : Assigns an element to a slot in Web Components.
├── spellcheck : Specifies whether to enable spelling and grammar checking (true, false).
├── style : Adds inline CSS styles to the element.
├── tabindex : Defines the tab order of an element (number).
├── title : Provides extra information as a tooltip when the user hovers over the element.
├── translate : Specifies whether the content should be translated (yes, no).
└── aria-* : Accessibility attributes used to improve interaction with assistive technologies (e.g., aria-label, aria-hidden).





```


# TAG Attributes
```html
<input>
   ├── autofocus: Controls if the input automatically gets focus (true, false)
   ├── checked: Controls if the input is preselected (true, false)
   ├── disabled: Controls if the input is disabled (true, false)
   ├── form: Associates the input with a form (form ID)
   ├── formaction: URL to send form data to (URL)
   ├── formenctype: Encoding type for form data (application/x-www-form-urlencoded, multipart/form-data, text/plain)
   ├── formmethod: HTTP method for form submission (GET, POST)
   ├── formnovalidate: Controls if the input should skip validation (true, false)
   ├── formtarget: Specifies where to display the form response (_self, _blank, _top, _parent)
   ├── max: Maximum value for the input (number)
   ├── maxlength: Maximum number of characters (number)
   ├── min: Minimum value for the input (number)
   ├── minlength: Minimum number of characters (number)
   ├── multiple: Allows multiple values (true, false)
   ├── name: Name of the input (string)
   ├── pattern: Regular expression pattern (regex)
   ├── placeholder: Placeholder text (string)
   ├── readonly: Controls if the input is read-only (true, false)
   ├── required: Specifies if the input is required (true, false)
   ├── size: Width of the input (number)
   ├── src: URL of the image (URL)
   ├── step: Step value for numeric inputs (number)
   ├── type: Type of the input (text, password, checkbox, radio, etc.)
   ├── value: Default value of the input (string)
   ├── width: Width of the input (number)

<select>
   ├── autofocus: Controls if the select automatically gets focus (true, false)
   ├── disabled: Controls if the select is disabled (true, false)
   ├── form: Associates the select with a form (form ID)
   ├── multiple: Allows multiple options to be selected (true, false)
   ├── name: Name of the select (string)
   ├── required: Specifies if the select is required (true, false)
   ├── size: Number of visible options (number)

<option>
   ├── disabled: Controls if the option is disabled (true, false)
   ├── label: Label for the option (string)
   ├── selected: Controls if the option is selected by default (true, false)
   ├── value: Value of the option (string)

<textarea>
   ├── autofocus: Controls if the textarea automatically gets focus (true, false)
   ├── cols: Number of visible columns (number)
   ├── disabled: Controls if the textarea is disabled (true, false)
   ├── form: Associates the textarea with a form (form ID)
   ├── maxlength: Maximum number of characters (number)
   ├── minlength: Minimum number of characters (number)
   ├── name: Name of the textarea (string)
   ├── placeholder: Placeholder text (string)
   ├── readonly: Controls if the textarea is read-only (true, false)
   ├── required: Specifies if the textarea is required (true, false)
   ├── rows: Number of visible rows (number)
   ├── wrap: Text wrapping mode (soft, hard)

<button>
   ├── autofocus: Controls if the button automatically gets focus (true, false)
   ├── disabled: Controls if the button is disabled (true, false)
   ├── form: Associates the button with a form (form ID)
   ├── formaction: URL to send form data to (URL)
   ├── formenctype: Encoding type for form data (application/x-www-form-urlencoded, multipart/form-data, text/plain)
   ├── formmethod: HTTP method for form submission (GET, POST)
   ├── formnovalidate: Controls if the button should skip validation (true, false)
   ├── formtarget: Specifies where to display the form response (_self, _blank, _top, _parent)
   ├── name: Name of the button (string)
   ├── type: Type of the button (submit, reset, button)
   ├── value: Value of the button (string)

<fieldset>
   ├── disabled: Controls if the fieldset is disabled (true, false)
   ├── form: Associates the fieldset with a form (form ID)
   ├── name: Name of the fieldset (string)

<legend>
   ├── None: Caption for the fieldset (string)

<label>
   ├── for: Specifies which input the label is for (input ID)
   ├── form: Associates the label with a form (form ID)
   ├── name: Name of the label (string)

<datalist>
   ├── None: List of predefined options (string)

<optgroup>
   ├── label: Label for the group of options (string)

<progress>
   ├── value: Current value of the progress (number)
   ├── max: Maximum value of the progress (number)

<meter>
   ├── value: Current value of the meter (number)
   ├── min: Minimum value of the meter (number)
   ├── max: Maximum value of the meter (number)
   ├── low: Low threshold value (number)
   ├── high: High threshold value (number)
   ├── optimum: Optimal value (number)

<details>
   ├── open: Specifies that the details are visible by default (true, false)

<summary>
   ├── None: Heading for the details (string)

<dialog>
   ├── open: Specifies that the dialog is open (true, false)

<form>
   ├── accept-charset: Character encoding for form submission (UTF-8, ISO-8859-1, etc.)
   ├── action: URL to send the form data to (URL)
   ├── autocomplete: Controls if the browser should autocomplete the form fields (on, off)
   ├── enctype: Encoding type for form data (application/x-www-form-urlencoded, multipart/form-data, text/plain)
   ├── method: HTTP method for form submission (GET, POST)
   ├── name: Name of the form (string)
   ├── novalidate: Controls if the form should skip validation (true, false)
   ├── target: Specifies where to display the form response (_self, _blank, _top, _parent)

<img>
   ├── alt: Alternative text for the image (string)
   ├── crossorigin: How the image should be fetched (anonymous, use-credentials)
   ├── height: Height of the image (number)
   ├── ismap: Specifies that the image is a server-side image map (true, false)
   ├── longdesc: Link to a detailed description (URL)
   ├── src: URL of the image (URL)
   ├── usemap: Name of the image map (#map)
   ├── width: Width of the image (number)

<svg>
   ├── height: Height of the SVG container (number)
   ├── width: Width of the SVG container (number)
   ├── viewBox: Position and dimension of the SVG viewport (string, e.g., "0 0 100 100")
   ├── xmlns: XML namespace for SVG (URL)

<canvas>
   ├── height: Height of the canvas (number)
   ├── width: Width of the canvas (number)

<video>
   ├── controls: Controls if video controls should be displayed (true, false)
   ├── crossorigin: How the video should be fetched (anonymous, use-credentials)
   ├── height: Height of the video (number)
   ├── loop: Controls if the video should loop (true, false)
   ├── muted: Controls if the video should be muted (true, false)
   ├── playsinline: Controls if the video should play inline on mobile devices (true, false)
   ├── preload: How the video should be loaded (auto, metadata, none)
   ├── src: URL of the video (URL)
   ├── width: Width of the video (number)

<audio>
   ├── controls: Controls if audio controls should be displayed (true, false)
   ├── crossorigin: How the audio should be fetched (anonymous, use-credentials)
   ├── loop: Controls if the audio should loop (true, false)
   ├── muted: Controls if the audio should be muted (true, false)
   ├── preload: How the audio should be loaded (auto, metadata, none)
   ├── src: URL of the audio (URL)

<source>
   ├── media: Media type for which the source is suitable (string, e.g., "screen and (min-width: 800px)")
   ├── src: URL of the media source (URL)
   ├── type: MIME type of the media source (string, e.g., "video/mp4")

<track>
   ├── default: Controls if the track should be the default (true, false)
   ├── kind: Kind of track (subtitles, captions, descriptions, chapters, metadata)
   ├── label: Label for the track (string)
   ├── src: URL of the track file (URL)
   ├── srclang: Language of the track (language code)

<map>
   ├── name: Name of the map (string)

<area>
   ├── alt: Alternative text for the area (string)
   ├── coords: Coordinates of the clickable area (numbers)
   ├── download: Specifies that the link should download a file (filename)
   ├── href: URL of the linked resource (URL)
   ├── media: Media type for which the area is suitable (string)
   ├── ping: URL to send a ping to (URL)
   ├── rel: Relationship between the current document and the linked resource (string)
   ├── shape: Shape of the clickable area (rect, circle, poly)
   ├── target: Where to display the linked resource (_self, _blank, _top, _parent)

<iframe>
   ├── allow: Features the iframe is allowed to use (string)
   ├── allowfullscreen: Specifies that the iframe is allowed to enter fullscreen mode (true, false)
   ├── frameborder: Whether the iframe should have a border (number)
   ├── height: Height of the iframe (number)
   ├── loading: When the iframe should be loaded (eager, lazy)
   ├── marginheight: Top and bottom margins of the iframe (number)
   ├── marginwidth: Left and right margins of the iframe (number)
   ├── name: Name of the iframe (string)
   ├── referrerpolicy: Referrer policy for the iframe (string)
   ├── sandbox: Sandboxing rules for the iframe (string)
   ├── src: URL of the iframe content (URL)
   ├── srcdoc: HTML content of the iframe (string)
   ├── width: Width of the iframe (number)
```