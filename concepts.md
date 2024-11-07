# HTML & CSS Learning Concepts

## Introduction
Welcome to my HTML and CSS learning documentation! This markdown file serves as a comprehensive collection of concepts, techniques, and best practices I'm learning throughout my web development journey. Coming from a Python background, I've started this documentation to track my progress and create a personal reference guide for web development fundamentals.

### Purpose of This Documentation
- Track and organize new concepts as I learn them
- Serve as a quick reference guide for future projects
- Document my progression from basics to advanced topics
- Create a searchable knowledge base of web development concepts

### How This Document is Organized
Each concept will be documented with:
- Clear explanations of what it does
- Basic syntax and usage examples
- Common use cases
- Best practices and conventions
- Personal notes and insights

# HTML Intro:

## What is HTML:
HTML stands for HyperText Markup Language, and is a standardized system for tagging text files to achieve font, color, graphic, and hyperlink effects on World Wide Web pages.

## HTML Syntax

The standard HTML syntax:

```html
<openingTag>
  This is how HTML elements are written
</closingTag> 
```

Each HTML element is represented as above, some basic HTML elements are:

```html
<p>This is a paragraph HTML element</p>

<button>This is a button HTML element</button>

<a href="https://github.com/tahadnan">
  My GitHub Account
  <!-- Hey, there's an indentation before me, P.S:I'M an HTML comment -->
</a>
```
* Notes:  
    + To make the HTML code look cleaner we use indentations, in HTML, it's 2 spaces.  
    + HTML comments are put between ```<!-- HTML comment -->```

As noticed above the ```a``` element is special as it has ```href="https://github.com/tahadnan"``` in its opening tag, we call ```href``` an attribute and ```"https://github.com/tahadnan"``` its value.  
An HTML attribute modifies the element's behaviour. So now when we click on "My Github Account" we'll be redirected to [my github account ^^](https://github.com/tahadnan).

* Notes:
    + HTML attributes must be within the opening tag.
    + There are several HTML attributes, some are element-specific and some are element-wide.

### Summary:
* HTML elements consist of opening and closing tags
* Basic syntax follows the pattern: ```<openingTag>content</closingTag>```
* Elements can have attributes in their opening tags that modify their behavior
* HTML uses 2-space indentation for cleaner code organization
* Comments are written using ```<!-- comment -->``` syntax

# CSS Intro:

## What is CSS
CSS (Cascading Style Sheets) is a styling language used to describe the presentation of HTML documents. It controls how webpage elements look and are laid out on the screen - from colors and fonts to spacing and positioning. The "cascading" part means styles can inherit and override each other following a specific hierarchy.

## CSS Syntax:
The standard CSS syntax:
```css
    .CSS_selector : {
        css_property: property_value;
    }
```
* Notes:
    + Each HTML element can have its proper css selector defined by the ```class``` attribute or we can just use the tag name.
    + As the project grows bigger and bigger using the class attribute becomes a necissity, otherwise the styles become mixed.
    + If light and small styling is intended we can use the ```style``` HTML element.

## Common CSS Properties

CSS properties control different aspects of an element's appearance. Here are some fundamental ones:

| Property | Description | Value Type |
|----------|-------------|------------|
| `background-color` | Changes the element's background color | Color value |
| `color` | Changes the element's content color | Color value |
| `border` | Controls the style, width, and color of an element's border | Multiple values |
| `height` | Sets the element's height | Length value |
| `width` | Sets the element's width | Length value |
| `margin` | Controls the space around the element | Length value |

### Length Values
Length properties (height, width, margin, etc.) can be specified using various units of measurement. Common units include:
- `px` (pixels)
- `em` (relative to font size)
- `rem` (relative to root font size)
- `%` (percentage)
- `vh` (viewport height)
- `vw` (viewport width)

*For a complete list of measurement units, refer to CSS_Units.png*

* Notes:
    + CSS comments uses 4 space indents for cleaner code.
    + CSS comments are written as ```/* This is a CSS comment */```

### Summary: