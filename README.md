## Github Markdown Cheatsheet

Go to the wiki page: 

[Github Markdown Cheatsheet Wiki](https://github.com/yasinnaal/Github-Markdown-Cheatsheet/wiki)

## Welcome to my Github Markdown Cheatsheet yn-github-markdown-cheatsheet

#### Table of Contents

## Common parameters can be used with URL 

* ``` title_color ``` - Card's title color (hex color). Default: 2f80ed.
* ``` text_color ``` - Body text color (hex color). Default: 434d58.
* ``` icon_color ``` - Icons color if available (hex color). Default: 4c71f2.
* ``` border_color ``` - Card's border color (hex color). Default: e4e2e2 (Does not apply when hide_border is enabled).
* ``` bg_color ``` - Card's background color (hex color) or a gradient in the form of angle,start,end. Default: fffefe
* ``` hide_border ``` - Hides the card's border (boolean). Default: false
* ``` theme ``` - name of the theme, choose from all available themes. Default: default theme.
* ``` cache_seconds ``` - set the cache header manually (min: 14400, max: 86400). Default: 14400 seconds (4 hours).
* ``` locale ``` - set the language in the card (e.g. cn, de, es, etc.). Default: en.
* ``` border_radius ``` - Corner rounding on the card. Default: 

[Headers](#Headers)<br>
[Emphasis (Style Text Bold, Italic, strikethrough)](#Emphasis)<br>
[Blockquotes](#Blockquotes)<br>
[Lists](#Lists)<br>
[Ordered List](#Ordered)<br>
[List CheckBox - Task Lists](#List-CheckBox-or-Tasks-Lists)<br>
[Email](#Email)<br>
[Code - Programing languages](#Code)<br>
[Links](#Links)<br>
[Line Breaks](#Line-Breaks)<br>
[Horizontal Line](#Horizontal-Line)<br>
[Tables](#Tables)<br>
[Images](#Images)<br>
[Emoji](#Emoji)<br>
[Shields Badges](#Shields-Badges)


## Headers

```
# H1
## H2
### H3
#### H4
##### H5
###### H6
```
# H1
## H2
### H3
#### H4
##### H5
###### H6

## Emphasis

```
*Text will be italic*

_Text will be italic_

**Text will be bold**

__Text  will be bold__

*You **can** combine them*

~~strikethrough text (deleted text)~~ or <del>strikethrough text (deleted text)</del>

```
*Text will be italic*

_Text will be italic_

**Text will be bold**

__Text will be bold__

*You **can** combine them*

~~strikethrough text (deleted text)~~ or <del>strikethrough text (deleted text)</del>

## Blockquotes

```
As Grace Hopper said:
> I’ve always been more interested
> in the future than in the past.
```
As Grace Hopper said:
> I’ve always been more interested
> in the future than in the past.

## Lists

```
* Item 1
* Item 2
  * Item 2a (add tow spaces manually)
  * Item 2b (add tow spaces manually)
* Item 3
```
* Item 1
* Item 2
  * Sub Item (add tow spaces manually)
  * Sub Item (add tow spaces manually)
* Item 3

## Ordered

```
1. Item 1
2. Item 2
  * Item 2a (add tow spaces manually)
  * Item 2b (add tow spaces manually)
3. Item 3
```
1. Item 1
2. Item 2
  * Item 2a (add space manually)
  * Item 2b (add space manually)
3. Item 3

## List CheckBox or Tasks Lists

```
- [ ] Item A
- [x] Item B
- [x] Item C
```
- [ ] Item A
- [x] Item B
- [x] Item C

## Email
```
<email@email.com>
```
<email@email.com>

## Code

You can add language identifier after ``` to enable syntax highlighting in code block.

ABAP
````
```ABAP
REPORT Z_HELLO_WORLD.

* ABAP Hello World!
" we use * or " to write comments, both are supported.

write 'Hello World'.
```
````

```ABAP
REPORT Z_HELLO_WORLD.

* ABAP Hello World!
" we use * or " to write comments, both are supported.

write 'Hello World'.
```

rubby
````
```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```
````
```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```

java
````
```java
// Your First java Program
class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!"); 
    }
}
```
````

```java
// Your First java Program
class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!"); 
    }
}
```

You can find out which programing language keywords are valid in the [languages YAML file](https://github.com/github/linguist/blob/master/lib/linguist/languages.yml).

## Links
```
[click here to go to Google](wwww.google.com)
```
[click here to go to Google](https://www.google.com/)

## Line Breaks
```
line 1<br>
line 2<br>
line 3<br>
```
line 1<br>
line 2<br>
line 3<br>

## Horizontal Line
```
Hyphens (Dash)
---

Asterisks
***

Underscores
___

```
Hyphens (Dash)
---

Asterisks
***

Underscores
___

## Tables
```
|Column 1|Column 2|Column 3|
|---|:---|---:|
|Row 1 Column 1| Row 1 Column 2| Row 1 Column 3|
|Row 2 Column 1| Row 2 Column 2| Row 2 Column 3|

Note: Colons : are used to align columns lef, right, center.
```
|Column 1|Column 2|Column 3|
|---|:---|---:|
|Row 1 Column 1| Row 1 Column 2| Row 1 Column 3|
|Row 2 Column 1| Row 2 Column 2| Row 2 Column 3|

## Images
```
![anytext](https://github.com/yasinnaal/images/blob/main/github_logo.png)

or

<img src="https://github.com/yasinnaal/images/blob/main/github_logo.png?raw=true">

or

to add tip text on mouse hover

![alt text](https://github.com/yasinnaal/images/blob/main/github_logo.png "Github Logo")
```
![alt text](https://github.com/yasinnaal/images/blob/main/github_logo.png "Github Logo")

## Emoji
[Emoji](https://github.com/yasinnaal/Github-Markdown-Cheatsheet/wiki/Emoji)<br>
[People](https://github.com/yasinnaal/Github-Markdown-Cheatsheet/wiki/Emoji#people) - (😊 , 😯 , ❤️)<br>
[Nature](https://github.com/yasinnaal/Github-Markdown-Cheatsheet/wiki/Emoji#nature) - (☀️ , ⛄ , 🐶)<br>
[Objects](https://github.com/yasinnaal/Github-Markdown-Cheatsheet/wiki/Emoji#objects) - (📁 , 💻 , 🔔)<br>
[Places](https://github.com/yasinnaal/Github-Markdown-Cheatsheet/wiki/Emoji#places) - (:house: , ⚠️ , 🗽)<br>
[Symbols](https://github.com/yasinnaal/Github-Markdown-Cheatsheet/wiki/Emoji#symbols) - (:parking: , ❌ , :wheelchair:)<br>
[Kaomoji](https://github.com/yasinnaal/Github-Markdown-Cheatsheet/wiki/Emoji#kaomoji)<br><br>
[Special-Symbols](https://github.com/yasinnaal/Github-Markdown-Cheatsheet/wiki/Emoji#special-symbols)<br><br>

## Shields Badges
See more:<br>
[https://shields.io/](https://shields.io/)<br>
[https://github.com/badges/shields](https://github.com/badges/shields)<br>

![ddd](https://img.shields.io/badge/license-MIT-green)<br>

![GitHub Repo forks](https://img.shields.io/github/forks/yasinnaal/Github-Markdown-Cheatsheet)<br>

![GitHub Repo stars](https://img.shields.io/github/stars/yasinnaal/Github-Markdown-Cheatsheet) <br>

You can search on [https://shields.io/](https://shields.io/) to see all github badges and create your own. <br>

You can show information about your repository like forks total...etc. 

---

References: [markdown cheatsheet online pdf](https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf)

