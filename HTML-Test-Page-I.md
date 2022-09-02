# HTML5 Test Page

This is a test page filled with common HTML elements that is intended to be a visual representation of how these elements will look with your CSS styles applied.

Note: as this is a Markdown file, not all HTML elements are supported in Markdown syntax. Therefore, you'll see some inline HTML elements. You'll also see some Markdown syntax for some features that are not supported on all Markdown parser platforms. I'm hoping to pick one that allows for some extra support of extended Markdown [^1] (or whatever it's called).

[^1]: There are various Markdown parsers. Not all are created equal.

## Text {#text}

### Headings {#headings}

# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

### Paragraphs {#paragraphs}

A paragraph (from the Greek paragraphos, “to write beside” or “written beside”) is a self-contained unit of a discourse in writing dealing with a particular point or idea. A paragraph consists of one or more sentences. Though not required by the syntax of any language, paragraphs are usually an expected part of formal writing, used to organize longer prose.

### Blockquotes {#blockquotes}

> A block quotation (also known as a long quotation or extract) is a quotation in a written document, that is set off from the main text as a paragraph, or block of text.

> It is typically distinguished visually using indentation and a different typeface or smaller size
quotation. It may or may not include a citation, usually placed at the bottom.

<cite>Said no one, ever</cite>

A paragraph of text here to ensure that these blockquotes are separated. Hopefully this will be adequate to provide ample space to spread 'em out.

<figure>
    <blockquote>That's no moon. That's a space station!</blockquote>
    <figcaption>Obi Wan Kenobi <cite>A New Hope</cite></figcaption>
</figure>

### Definition List {#definition-list}

Definition List Title
: This is a definition list division

Another Definition List Title
: This is the first definition
: This is the second definition

### Ordered List {#ordered-list}

1. List Item 1
1. List Item 2
    1. List Item 1
    1. List Item 2
        1. List Item 1
        1. List Item 2
            1. List Item 1
            1. List Item 2
                1. List Item 1
                1. List Item 2
                1. List Item 3
            1. List Item 3
        1. List Item 3
    1. List Item 3
1. List Item 3

### Unordered List {#unordered-list}

* List Item 1
* List Item 2
    * List Item 1
    * List Item 2
        * List Item 1
        * List Item 2
            * List Item 1
            * List Item 2
                * List Item 1
                * List Item 2
                * List Item 3
            * List Item 3
        * List Item 3
    * List Item 3
* List Item 3

### Details/Summary {#details-summary}

<details>
    <summary>What time is it when an elephant sits on a fence?</summary>
    Time to get a new fence!
</details>

### Address {#address}

<address>
    Written by
    <a href="mailto:webmaster@example.com">Jon Doe</a>
    <br>Visit us at:
    <br>1313 Mockingbird Ln
    <br>Transylvannia, OR 90210
    <br>United States of America
</address>

### Horizontal Rule {#horizontal-rule}

---

### Tables {#tables}

|Heading 1|Heading 2|Heading 3|Heading 4|Heading 5|
|---|---|---|---|---|
|Cell 1|Cell 2|Cell 3|Cell 4|Cell 5|
|Cell 1|Cell 2|Cell 3|Cell 4|Cell 5|
|Cell 1|Cell 2|Cell 3|Cell 4|Cell 5|
|Cell 1|Cell 2|Cell 3|Cell 4|Cell 5|

### Code {#code}

Keyboard input: <kbd>c</kbd><kbd>m</kbd><kbd>d</kbd>

### Inline Code:

```java
    system.out.println("Hello World")
```

Sample output:

<samp>Keyboard not found<br>Press F1 to continue&hellip;</samp>

### Task Lits

- [x] Make Money :dollar:
- [x] Drink Beer :beer:
- [ ] Get Females :girl:

### Emojis

:laughing:

[Markdown Emojis](https://gist.github.com/rxaviers/7360908)

### Pre-Formatted Text {#pre-formated-text}

<pre>
P R E F O R M A T T E D T E X T
! " # $ % &amp; ' ( ) * + , - . /
0 1 2 3 4 5 6 7 8 9 : ; &lt; = &gt; ?
@ A B C D E F G H I J K L M N O
P Q R S T U V W X Y Z [ \ ] ^ _
` a b c d e f g h i j k l m n o
p q r s t u v w x y z { | } ~
</pre>

### Inline Elements {#inline-elements}

[This is a text link]("#")

**Strong is used to indicate strong importance**

*This text has added emphasis*

The **b element** is stylistically different text from normal text, without any special importance.


The *i element* is text that is offset from the normal text.

The <u>u element</u> is text with an unarticulated, though explicitly rendered, non-textual annotation.

<del>this text is deleted</del>

and <ins>this text is inserted</ins>

~~this text has a strikethrough~~

Superscript^2^

Subscript for things like H~2~O

<small>This small text is for fine print or something similar</small>

Abbreviation: <abbr title="Hyper Text Markup Language">HTML</abbr>

<q cite="https://www.google.com">This is a short inline quotation.</q>

<cite>This is a citation.</cite>

A dfn element, <dfn>validator</dfn> is a program that checks for syntax errors in code or documents.

The ==mark element== indicates highlighted text

The <var>variable element</var>, such as <var>x</var> = <var>y</var>.

The time element: <time datetime="2022-08-17">August 17^th^, 2022</time>

## Images {#images}

### Figure

<figure>
    <img src="https://picsum.photos/400/400" alt="Photo of a kitten">
</figure>

### Figure + Figcaption

<figure>
    <img src="https://picsum.photos/500/500" alt="Photo of a kitten">
    <figcaption>Photo of a kitten with a figcaption <cite>and a cite</cite></figcaption>
</figure>

### Figure + Picture

<figure>
    <picture>
        <source srcset="https://picsum.photos/800/800" media="(min-width: 800px)">
        <img src="https://picsum.photos/800/800" alt="Photo of a kitten">
    </picture>
</figure>

## Embedded Content {#embedded-content}

### Audio
<audio controls src="https://file-examples.com/storage/fe6a5406fa63112369b75a2/2017/11/file_example_OOG_1MG.ogg" type="audio/ogg"></audio>

### Video

<video controls src="https://file-examples.com/storage/fe6a5406fa63112369b75a2/2018/04/file_example_OGG_480_1_7mg.ogg" type="video/ogg"></video>

## Meter

<meter value="5" min="0" max="10">5 out of 10</meter>

## Progress

<progress value="50" max="100">50%</progress>

## Inline SVG

<svg width="100px" height="100px">
    <circle cx="100" cy="100" r="100" fill="#1fa3ec"></circle>
</svg>

## Form Elements

<form>
    <fieldset id="textFields">
        <legend>Input Fields</legend>
        <label for="textInput">Name</label>
        <input type="text" id="textInput" minlength="10" maxlength="30" size="20"
            placeholder="Enter your name" autocomplete="name">
        <br>
        <label for="passwordInput">Password</label>
        <input type="password" id="passwordInput" minlength="10" placeholder="Type your secret password"
            autocomplete="current-password">
        <br>
        <label for="webAddress">Website</label>
        <input type="url" id="webAddress" pattern="(https?:\/\/(?:www\.|(?!www)).*" size="30"
            placeholder="https://www.google.com" autocomplete="url">
        <br>
        <label for="emailAddress">Email Address</label>
        <input type="email" id="emailAddress" pattern=".+@[a-zA-Z]{1,}\.[a-z]{2,}"
            placeholder="Enter your email address" autocomplete="email">
        <br>
        <label for="phoneNumber">Phone Number</label>
        <input type="tel" id="phoneNumber" placeholder="801-867-5309" pattern="[0-9]{3}-[0-9]{3}-[0-9]{4}"
            autocomplete="tel">
        <br>
        <label for="searchField">Search</label>
        <input type="search" id="searchField" placeholder="Enter a search term">
        <button>Search</button>
        <br>
        <label for="fileInput">File Input</label>
        <input type="file" id="fileInput" accept="image/jpeg, image/png">
        <br>
    </fieldset>
    <fieldset id="selectFields">
        <legend>Select Menu</legend>
        <label for="selectOptions">Select Options</label>
        <select id="selectOptions">
            <optgroup label="Option Group">
                <option value="1">Option 1</option>
                <option value="2">Option 2</option>
                <option value="3">Option 3</option>
            </optgroup>
        </select>
        <br>
        <br>
        <label for="multipleSelect">Select Multiple</label>
        <select id="multipleSelect" multiple="multiple" size="4">
            <optgroup label="Option Group">
                <option value="1">Option 1</option>
                <option value="2">Option 2</option>
                <option value="3">Option 3</option>
            </optgroup>
        </select>
        <br>
        <br>
        <label for="dataList">Data List</label>
        <input list="fruit" id="dataList" name="datList">
        <datalist id="fruit">
            <option value="Apple">
            <option value="Orange">
            <option value="Strawberry">
            <option value="Kiwi">
            <option value="Banana">
        </datalist>
    </fieldset>
    <fieldset id="checkboxes">
        <legend>Checkboxes</legend>
        <label for="checkbox1">
            <input type="checkbox" name="checkbox" id="checkbox1" checked="checked">Choice 1
        </label>
        <br>
        <label for="checkbox2">
            <input type="checkbox" name="checkbox" id="checkbox2">Choice 2
        </label>
        <br>
        <label for="checkbox3">
            <input type="checkbox" name="checkbox" id="checkbox3">Choice 3
        </label>
        <br>
        <br>
        <input type="radio" name="ducks" id="radio1">
        <label for="radio1">Huey</label>
        <br>
        <input type="radio" name="ducks" id="radio2" checked="checked">
        <label for="radio2">Dewey</label>
        <br>
        <input type="radio" name="ducks" id="radio3">
        <label for="radio3">Louie</label>
        <br>
    </fieldset>
    <fieldset id="textareas">
        <legend>Text Areas</legend>
        <label for="textarea">Textarea</label>
        <textarea id="textarea" rows="8" cols="48" placeholder="Enter your message here"></textarea>
    </fieldset>
    <fieldset id="html5">
        <legend>HTML5 Inputs</legend>
        <label for="colorInput">Color Input</label>
        <input type="color" id="colorInput" value="#000000">
        <br>
        <label for="numberInput">Number Input</label>
        <input type="number" id="numberInput" min="0" max="10" value="5">
        <br>
        <label for="rangeInput">Range Input</label>
        <input type="range" id="rangeInput" min="0" max="100" value="30" step="10">
        <br>
        <label for="dateInput">Date Input</label>
        <input type="date" id="dateInput" min="2000-01-01" max="2022-01-01" value="2011-01-01"
            autocomplete="bday">
        <br>
        <label for="monthInput">Month Input</label>
        <input type="month" id="monthInput" min="2000-01" value="2010-01">
        <br>
        <label for="weekInput">Week Input</label>
        <input type="week" id="weekInput" min="2000-W01" value="2005-W01">
        <br>
        <label for="timeInput">Time Input</label>
        <input type="time" id="timeInput" min="00:00" max="23:59" value="14:30">
        <br>
        <label for="dateTimeLocalInput">Date Time Local Input</label>
        <input type="datetime-local" id="dateTimeLocalInput" value="1970-01-01T00:00">
        <br>
    </fieldset>
    <fieldset id="buttons">
        <legend>Action Buttons</legend>
        <input type="submit" value="Submit">
        <br>
        <input type="button" value="Button">
        <br>
        <input type="reset" value="Reset">
        <br>
        <input type="submit" value="Submit Disabled" disabled="disabled">
        <br>
    </fieldset>
</form>
