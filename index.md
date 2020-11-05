# Things I have learned today

## Fundamentals of web apps

_2020/11/02_

Week 1 Monday

1. git add . = update everything in the current folder.
2. git add \* = update everything.
3. git log = see all the commits i have done so far.
4. DevTools had a dark theme.
5. ../ and .. meaning the same thing.
6. Learned more commands.

   - echo = to repeat whatever i said.
   - date = to see the current date.
   - pwd = to see my current file location.
   - ls = to see lists of files and folders.
   - history = to see all commands i have typed so far.
   - rmdir = removes empty folder.
   - rm -R dir = removes non-empty directory.
   - cp = copy file.
   - mv = moves or renames file. (mv ./from ./to)
   - Difference between mkdir and touch. (empty directory and empty file)

7. Interesting method of using html to link with google server by simply using form/input/submit.
8. Alternative method of creating repo.
9. First time using Markdown. Its interesting.

---

## Basic HTML & CSS

_2020/11/03_

Week 1 Tuesday

### HTML

1.  Hyper text markup language

2.  dom = document object model
    "The Document Object Model (DOM) is a programming interface for HTML documents."
    -MDN web docs-

3.  `<a target="_blank"></a>` opens to a new tab

4.  lorem gives random texts

5.  `<hr>` horizontal line

6.  ordered list gives bullet list in order. `<ul></ul>` unordered list doesnt.

```
<ol>
<li></li>
</ol>
```

7.  `<table>` gives tabular data

    `<thead>` Defines a group of table rows `<tr>` at the start of a `<table>`.

    `<tfoot>` Defines a group of table rows `<tr>` at the end of a `<table>`.

    `<tr>` defines one table row.

    `<td>` Defines a table cell. Must be a direct child of a `<tr>`.

    -definition from htmlreference.io-

8.  `<strong></strong>` or `<b></b>` makes string become bold

9.  `<em></em>` makes string cursive

10. `<!--whatever-->` disables codes just like //

11. HTML element
    element
    Start tag (attribute name, value) → Content → End tag

    `{<div class="classExample">}{Content Example.}{</div>}`

12. Inline/block value

    https://developer.mozilla.org/en-US/docs/Web/CSS/display

### CSS

1. Attribute selector

   The CSS attribute selector matches elements based on the presence or value of a given attribute.

   https://developer.mozilla.org/en-US/docs/Web/CSS/Attribute_selectors

   pseudo-class selector

   :

   a keyword added to a selector that specifies a special state of the selected element(s).

   https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-classes

   pseudo-element selector

   ::

   is a keyword added to a selector that lets you style a specific part of the selected element(s).

   https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-elements

   combinators

   they combine other selectors in a way that gives them a useful relationship to each other and the location of content in the document.

   - Decendant selector (space)
   - Child selector (>)
   - Adjacent sibling selector (+)
   - General sibling selector (~)

   https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Selectors/Combinators

2. Absolute length units are the fixed length units.
   Relative length units are the length units relative to something else.

   Absolute length units

   - cm = centimeters
   - mm = millimeters
   - in = inches
   - pc = picas = 4.23mm
   - pt = points = 0.35mm
   - px = pixels = 0.26mm

   Relative length units

   - em = font size depending to the parent of the element
   - rem = font size depending to the root of the element
   - vw = 1% of the viewpoint's width
   - vh = 1% of the viewpoint's height
   - vmin = uses the smallest viewpoint of width or height in percentage
   - vmax = uses the largest viewpoint of width or height in percentage

3. CSS box sizing

   - width/ height = controls the content area
   - padding = to add some meat to the content area
   - border = just border around the content area
   - margin = spacing around the content area

4. Cascade

   an algorithm that defines how to combine property values originating from different sources.

5. Specificity
   - more id
   - most class
   - most tag names
   - location of style (from lowest to highest)
   - Default→External Stylesheet (style.css)→Internal Stylesheet (head)→Element Style (inline)

### Additional Links

Cheatsheet

https://htmlcheatsheet.com/

HTML reference

https://htmlreference.io/

CSS reference

https://cssreference.io/

Colors

https://flatuicolors.com/
