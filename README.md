# CSS Cheat Sheet notebook.
This a document created only for have it on hand when it's need it and i it will teach a quick resource of the bases of CSS. Let's get started.

## 1. Propper Method to add CSS
There are 3 ways two add CSS: **Inline**, **Internal** and **External** the one that's correct for good practices is: **External** CSS File to be added on our html file.


## 2. CSS Selector
|  Selector    | Property   | Value    | Declaration End   |
|--------------|------------|----------|-------------------|
|       a      |{ background-color:|yellow}| ;|
||{ -> declaration start |: -> property/value separator|declaration separator|

##	3. Colors In CSS
There are different ways to apply color in CSS.
> p { color: blue; }
- Color names.
- HTML 5 Color names.
- Hexadecimal
- RGB

## 4. Fonts

There are common font types and subtypes some of these font types are:
- Sans-Serif
- Serif
- Monospace
- Cursive
- Fantasy

## 5. Box Model
Each box has four areas which are: content, padding, border and margin.

- **Content** consists of content like text, image, or other media content. It is bounded by the content edge and its dimensions are given by **content box** width and height.
:sparkles: Example:
	 > .class-name {  
	   box-sizing: content-box
	}

**Padding:** It includes the element’s padding. This area is actually the space around the content area and within the border box. Its dimensions are given by the width of the padding-box and the height of the padding-box.

**Border:** It is the area between the box’s padding and margin. Its dimensions are given by the width and height of border.

**Margin:** This area consists of space between border and margin. The dimensions of Margin area are the margin-box width and the margin-box height. It is useful to separate the element from its neighbors.

### Margin and padding shorthand:
> p {
		margin-top: 5px;
		margin-bottom: 5px;
		margin-right: 5px;
		margin-left: 5px;
> }

Shorthand
> p {
> margin: 5px 10px 5px 10px;
> }

Shorthand top and bottom, left and right.
> p {
> margin: 5px 10px;
> }
>
## 6. Position In CSS
Some values for  posistioning property in CSS:

- **Static**
- **Relative**
-  **Absolute**
-  **Fixed**
-  **Initial**
-  **Inherit**
