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

# Attributes values
- [Global Attributes](#global-attributes)
- [Tag Attributes with values](#tag-attributes)
- [Tag wise events](#tag-events)


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















# HTML attributes along with their possible value types

## Global Attributes

```yaml
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
```yaml

<html>
  ├── lang: "en", "fr", "es", etc.
  └── xmlns: "http://www.w3.org/1999/xhtml"



<head>
  ├── <meta>
  │    ├── charset: "UTF-8", "ISO-8859-1", etc. (character encoding)
  │    ├── name: "description", "keywords", "author", "viewport", "robots", etc. (metadata name)
  │    ├── content: "text" (content associated with the name)
  │    ├── http-equiv: "refresh", "content-security-policy", "X-UA-Compatible" (HTTP header control)
  │    └── viewport: "width=device-width, initial-scale=1.0" (controls layout on mobile browsers)
  ├── <link>
  │    ├── rel: "stylesheet", "icon", "preload", "preconnect", "alternate", "manifest", etc. (relationship to the document)
  │    ├── href: "URL" (URL of the linked resource)
  │    ├── type: "text/css", "image/png", etc. (MIME type of the linked resource)
  │    ├── sizes: "size" (size for icons)
  │    ├── media: "screen", "print", "all", etc. (media type for styles)
  │    └── title: "text" (title of the linked resource)
  ├── <style>
  │    ├── type: "text/css" (MIME type)
  │    ├── media: "screen", "print", etc. (media type for styles)
  │    └── scoped: "" (applies styles only to the parent element)
  ├── <base>
  │    ├── href: "URL" (base URL for relative URLs)
  │    └── target: "_self", "_blank", "_parent", "_top" (default target for all links)
  └── <title>
       └── None


<body>
  ├── alink: "#FF0000" (deprecated)
  ├── background: "URL" (deprecated)
  ├── bgcolor: "#FFFFFF" (deprecated)
  ├── link: "#0000FF" (deprecated)
  ├── text: "#000000" (deprecated)
  ├── vlink: "#800080" (deprecated)
  ├── onload: "JavaScriptFunction()"
  └── onunload: "JavaScriptFunction()"

<h1> to <h6>
  └── align: "left", "center", "right", "justify" (deprecated)

<p>
  └── align: "left", "center", "right", "justify" (deprecated)

<br>
  └── None

<hr>
  ├── align: "left", "center", "right" (deprecated)
  ├── noshade: "" (deprecated)
  ├── size: "1" to "n"
  └── width: "100%", "50%", etc.

<pre>
  └── None

<blockquote>
  └── cite: "URL"

<code>
  └── None

<b>, <i>, <u>, <small>, <strong>, <em>, <mark>, <sup>, <sub>, <abbr>, <cite>, <q>, <span>
  └── None

<div>
  └── align: "left", "center", "right", "justify" (deprecated)

<section>, <article>, <aside>, <header>, <footer>, <main>, <nav>, <figure>, <figcaption>
  └── None


# List and Definition Elements
  ├── <ul>, <ol>
  │    ├── type: "disc", "circle", "square" (for <ul>) or "1", "A", "a", "I", "i" (for <ol>; specifies the bullet or numbering style)
  │    └── compact: "" (deprecated; suggests a more compact list)
  ├── <li>
  │    └── value: "number" (specifies the value of the list item for ordered lists)
  └── <dl>, <dt>, <dd>



# Table Elements
  ├── <table>
  │    ├── align: "left", "center", "right" (deprecated; alignment of the table)
  │    ├── bgcolor: "#FFFFFF" (deprecated; background color of the table)
  │    ├── border: "1" (width of the table border)
  │    ├── cellpadding: "1" to "n" (space between cell walls and content)
  │    ├── cellspacing: "1" to "n" (space between table cells)
  │    ├── frame: "void", "above", "below", "hsides", "lhs", "rhs", "vsides", "box", "border" (which sides to render the border)
  │    ├── rules: "none", "groups", "rows", "cols", "all" (rules for displaying borders)
  │    ├── summary: "text" (summary of the table's content)
  │    └── width: "100%", "50%", etc. (width of the table)
  ├── <tr>
  │    ├── align: "left", "center", "right" (alignment of the row)
  │    ├── bgcolor: "#FFFFFF" (deprecated; background color of the row)
  │    └── valign: "top", "middle", "bottom", "baseline" (vertical alignment of content)
  ├── <td>, <th>
  │    ├── abbr: "text" (abbreviated text for accessibility)
  │    ├── align: "left", "center", "right" (alignment of the cell)
  │    ├── axis: "text" (relationship of the cell to other headers)
  │    ├── bgcolor: "#FFFFFF" (deprecated; background color of the cell)
  │    ├── colspan: "1" to "n" (number of columns the cell should span)
  │    ├── headers: "header_id" (IDs of associated headers)
  │    ├── rowspan: "1" to "n" (number of rows the cell should span)
  │    ├── valign: "top", "middle", "bottom", "baseline" (vertical alignment of content)
  │    └── width: "100px", "50%" (width of the cell)
  ├── <thead>, <tbody>, <tfoot>
  │    ├── align: "left", "center", "right" (alignment of the section)
  │    ├── bgcolor: "#FFFFFF" (deprecated; background color of the section)
  │    └── valign: "top", "middle", "bottom", "baseline" (vertical alignment of content)
  └── <colgroup>, <col>
       ├── align: "left", "center", "right" (deprecated; alignment of the column)
       ├── span: "number" (number of columns that this group or column should span)
       └── width: "100px", "50%" (width of the column)



- <a> (Anchor Tag Attributes)
  ├── href: "URL" (specifies the link target)
  ├── target: "_blank", "_self", "_parent", "_top", "framename"
  │    ├── _blank: (opens the link in a new tab or window)
  │    ├── _self: (opens the link in the same frame as it was clicked)
  │    ├── _parent: (opens the link in the parent frame)
  │    ├── _top: (opens the link in the full body of the window)
  │    └── framename: (opens the link in a named frame)
  ├── rel: "alternate", "author", "bookmark", "external", "help", "license", "nofollow", "noopener", "noreferrer", "prev", "next"
  │    ├── alternate: (indicates an alternate version of the document)
  │    ├── author: (links to the author of the document)
  │    ├── bookmark: (permanent URL used for bookmarking)
  │    ├── external: (indicates that the link is external)
  │    ├── help: (links to a help document)
  │    ├── license: (indicates a link to a copyright license)
  │    ├── nofollow: (tells search engines not to follow the link)
  │    ├── noopener: (prevents the new page from controlling the original page)
  │    ├── noreferrer: (prevents sending referrer information)
  │    ├── prev: (indicates the previous document in a series)
  │    └── next: (indicates the next document in a series)
  ├── download: "filename" (suggests a filename for downloading the file)
  ├── hreflang: "language_code" (specifies the language of the linked document)
  │    └── Examples: "en", "fr", "es", "de", "it", "jp" (English, French, Spanish, German, Italian, Japanese)
  ├── type: "MIME_type" (specifies the media type of the linked document)
  │    └── Examples: "text/html", "image/png", "application/pdf"
  ├── ping: "URL" (specifies a space-separated list of URLs to notify when the link is clicked)
  ├── referrerpolicy: "no-referrer", "no-referrer-when-downgrade", "origin", "origin-when-cross-origin", "same-origin", "strict-origin", "strict-origin-when-cross-origin", "unsafe-url"
  │    ├── no-referrer: (no referrer information is sent)
  │    ├── no-referrer-when-downgrade: (referrer is sent if the protocol is secure)
  │    ├── origin: (sends only the origin of the document as referrer)
  │    ├── origin-when-cross-origin: (sends full referrer for same-origin, origin only for cross-origin)
  │    ├── same-origin: (sends referrer only for same-origin requests)
  │    ├── strict-origin: (sends origin only if the protocol is secure)
  │    ├── strict-origin-when-cross-origin: (sends origin for cross-origin if the protocol is secure)
  │    └── unsafe-url: (sends full URL as referrer)
  ├── name: "text" (specifies the name of the anchor for internal linking)
  ├── id: "text" (specifies a unique id for the anchor element)
  ├── title: "text" (specifies additional information about the link)
  └── accesskey: "character" (specifies a shortcut key to activate/focus the link)



<form>
  ├── <form>
  │    ├── action: "URL" (URL to submit the form data)
  │    ├── method: "GET", "POST" (HTTP method to use for form submission)
  │    ├── enctype: "application/x-www-form-urlencoded", "multipart/form-data", "text/plain" (encoding type for form data)
  │    ├── target: "_self", "_blank", "_parent", "_top" (where to display the response)
  │    ├── novalidate: "" (disables form validation)
  │    ├── accept-charset: "UTF-8" (character encodings for form submission)
  │    └── autocomplete: "on", "off" (controls autocomplete feature)
  ├── <input>
  │    ├── type: "text", "password", "email", "number", "checkbox", "radio", "file", "hidden", "submit", "button", "url", "tel", "color", "date", "time", "range", etc. (input type)
  │    ├── name: "name" (name of the input)
  │    ├── value: "text" (default value of the input)
  │    ├── placeholder: "text" (placeholder text)
  │    ├── required: "" (makes input mandatory)
  │    ├── disabled: "" (disables the input)
  │    ├── readonly: "" (makes input read-only)
  │    ├── minlength: "number" (minimum number of characters)
  │    ├── maxlength: "number" (maximum number of characters)
  │    ├── pattern: "regex" (regular expression for input validation)
  │    ├── autocomplete: "on", "off" (autocomplete feature)
  │    └── tabindex: "number" (tab order of the element)
  ├── <textarea>
  │    ├── name: "name" (name of the textarea)
  │    ├── rows: "number" (number of visible text lines)
  │    ├── cols: "number" (visible width in characters)
  │    ├── placeholder: "text" (placeholder text)
  │    ├── required: "" (makes textarea mandatory)
  │    └── readonly: "" (makes textarea read-only)
  ├── <select>
  │    ├── name: "name" (name of the select element)
  │    ├── multiple: "" (allows multiple selections)
  │    ├── required: "" (makes select mandatory)
  │    ├── size: "number" (number of visible options)
  │    └── autocomplete: "on", "off" (autocomplete feature)
  │       └── <option>
  │            ├── value: "value" (value of the option)
  │            ├── selected: "" (default selected option)
  │            ├── disabled: "" (disables the option)
  │            └── label: "text" (label for the option)
  ├── <button>
  │    ├── type: "submit", "reset", "button" (button type)
  │    ├── name: "name" (name of the button)
  │    ├── value: "text" (value sent with the form)
  │    ├── disabled: "" (disables the button)
  │    └── formaction: "URL" (URL for the button's action)
  ├── <label>
  │    ├── for: "id" (associates label with input)
  │    └── None
  ├── <fieldset>
  │    ├── disabled: "" (disables all elements within the fieldset)
  │    ├── form: "id" (associates with a form)
  │    ├── name: "name" (name of the fieldset)
  │    └── <legend>
  │         └── None
  ├── <datalist>
  │    └── <option>
  │         └── value: "text" (value for the datalist options)
  ├── <progress>
  │    ├── value: "number" (current value)
  │    └── max: "number" (maximum value)
  ├── <meter>
  │    ├── value: "number" (current value)
  │    ├── min: "number" (minimum value)
  │    └── max: "number" (maximum value)
  └── None



<img>
  ├── src: "image-url" (path to the image)
  ├── alt: "alternative text" (description of the image)
  ├── width: "number" (width of the image in pixels)
  ├── height: "number" (height of the image in pixels)
  ├── loading: "lazy", "eager" (loading strategy)
  └── usemap: "#map-name" (associates image with a <map> element)

<video>
  ├── src: "video-url" (path to the video file)
  ├── controls: "" (shows playback controls)
  ├── autoplay: "" (plays video automatically)
  ├── loop: "" (replays video when finished)
  ├── muted: "" (starts video muted)
  ├── playsinline: "" (plays video inline on mobile)
  ├── poster: "image-url" (thumbnail image before playback)
  ├── width: "number" (width of the video in pixels)
  └── height: "number" (height of the video in pixels)

<audio>
  ├── src: "audio-url" (path to the audio file)
  ├── controls: "" (shows playback controls)
  ├── autoplay: "" (plays audio automatically)
  ├── loop: "" (replays audio when finished)
  ├── muted: "" (starts audio muted)
  ├── preload: "none", "metadata", "auto" (loading strategy)
  └── volume: "number" (volume level from 0.0 to 1.0, not an attribute)

<source>
  ├── src: "media-url" (path to the media file)
  ├── type: "audio/mpeg", "video/mp4", "image/jpeg", etc. (media type)
  └── media: "media-query" (condition to apply the source)

<track>
  ├── src: "track-url" (path to the track file)
  ├── kind: "subtitles", "captions", "descriptions", "chapters", "metadata" (type of track)
  ├── srclang: "language-code" (language of the track)
  ├── label: "track-label" (label for the track)
  ├── default: "" (indicates the default track)
  └── None

<map>
  └── name: "map-name" (identifier for the map)

<area>
  ├── shape: "rect", "circle", "poly" (shape of the clickable area)
  ├── coords: "coordinates" (coordinates for the shape)
  ├── href: "URL" (destination URL)
  ├── alt: "alternative text" (description of the area)
  ├── target: "_self", "_blank", "_parent", "_top" (where to open the link)
  └── rel: "nofollow", "noopener", "noreferrer" (relationship to the linked resource)

<canvas>
  ├── width: "number" (width of the canvas)
  ├── height: "number" (height of the canvas)
  └── None

<svg>
  └── None

<iframe>
  ├── src: "URL" (source of the iframe content)
  ├── width: "number" (width of the iframe in pixels)
  ├── height: "number" (height of the iframe in pixels)
  ├── frameborder: "0" (border of the iframe, deprecated)
  ├── allowfullscreen: "" (allows fullscreen mode)
  ├── loading: "lazy", "eager" (loading strategy)
  ├── title: "description" (title for accessibility)
  └── sandbox: "allow-same-origin", "allow-scripts", "allow-forms", etc. (restricts iframe capabilities)

<script>
  ├── src: "script-url" (path to an external script file)
  ├── async: "" (downloads script asynchronously)
  ├── defer: "" (executes script after document parsing)
  ├── type: "text/javascript", "module" (type of script)
  ├── charset: "character-set" (character encoding)
  └── None

<noscript>
  └── None

<template>
  └── None

<canvas>
  ├── width: "number" (width of the canvas)
  ├── height: "number" (height of the canvas)
  └── None

<slot>
  └── None

<iframe>
  ├── src: "URL" (source of the iframe content)
  ├── width: "number" (width of the iframe in pixels)
  ├── height: "number" (height of the iframe in pixels)
  ├── frameborder: "0" (border of the iframe, deprecated)
  ├── allowfullscreen: "" (allows fullscreen mode)
  ├── loading: "lazy", "eager" (loading strategy)
  ├── title: "description" (title for accessibility)
  └── sandbox: "allow-same-origin", "allow-scripts", "allow-forms", etc. (restricts iframe capabilities)

```


## TAG Events

```html


- HTML Element Events
  ├── <a>
  │    ├── onclick
  │    ├── onmouseover
  │    ├── onmouseout
  │    ├── onfocus
  │    ├── onblur
  │    ├── onmouseenter
  │    ├── onmouseleave
  │    ├── oncontextmenu
  │    └── ondrag
  ├── <button>
  │    ├── onclick
  │    ├── onfocus
  │    ├── onblur
  │    ├── onmousedown
  │    ├── onmouseup
  │    ├── onmouseenter
  │    ├── onmouseleave
  │    └── oncontextmenu
  ├── <form>
  │    ├── onsubmit
  │    ├── onreset
  │    ├── onchange
  │    ├── onfocus
  │    ├── onblur
  │    └── oninput
  ├── <input>
  │    ├── onchange
  │    ├── oninput
  │    ├── onfocus
  │    ├── onblur
  │    ├── onkeydown
  │    ├── onkeyup
  │    ├── onkeypress
  │    ├── onmousedown
  │    └── onmouseup
  ├── <select>
  │    ├── onchange
  │    ├── onfocus
  │    ├── onblur
  │    ├── onmousedown
  │    └── onmouseup
  ├── <textarea>
  │    ├── onchange
  │    ├── oninput
  │    ├── onfocus
  │    ├── onblur
  │    ├── onkeydown
  │    ├── onkeyup
  │    ├── onkeypress
  │    ├── onmousedown
  │    └── onmouseup
  ├── <img>
  │    ├── onerror
  │    ├── onclick
  │    ├── onload
  │    ├── onmouseover
  │    └── onmouseout
  ├── <video>, <audio>
  │    ├── onplay
  │    ├── onpause
  │    ├── onended
  │    ├── ontimeupdate
  │    ├── onloadstart
  │    ├── onloadeddata
  │    ├── onloadedmetadata
  │    └── onerror
  ├── <div>, <span>
  │    ├── onclick
  │    ├── onmouseover
  │    ├── onmouseout
  │    ├── onfocus
  │    ├── onblur
  │    ├── ondrag
  │    ├── ondragstart
  │    ├── ondragend
  │    ├── ondragover
  │    └── ondrop
  ├── <table>
  │    ├── onclick
  │    ├── onmouseover
  │    ├── onmouseout
  │    └── oncontextmenu
  ├── <body>
  │    ├── onload
  │    ├── onunload
  │    ├── onfocus
  │    ├── onblur
  │    └── onresize
  ├── <window>
  │    ├── onresize
  │    ├── onscroll
  │    ├── onunload
  │    ├── onload
  │    ├── onfocus
  │    └── onblur
  ├── <document>
  │    ├── onDOMContentLoaded
  │    ├── onload
  │    ├── onvisibilitychange
  │    ├── onkeydown
  │    ├── onkeyup
  │    ├── onkeypress
  │    └── onerror
  ├── <dl>
  │    ├── onclick
  │    ├── onmouseover
  │    ├── onmouseout
  │    ├── onfocus
  │    └── onblur
  ├── <dt>
  │    ├── onclick
  │    ├── onmouseover
  │    └── onmouseout
  ├── <dd>
  │    ├── onclick
  │    ├── onmouseover
  │    └── onmouseout
  ├── <colgroup>
  │    ├── onclick
  │    ├── onmouseover
  │    └── onmouseout
  └── <col>
       ├── onclick
       ├── onmouseover
       └── onmouseout
```
