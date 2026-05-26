# HTML

**What is HTML?**
* html is stands for `HyperText Markup Language `
* It is used for creating  the structure of webpage
* The Structure we want to create for that we have many tags in html.
#
**What is HyperText?**
* Any text that contains link of of any other webpage is called as hypertext.
#
**Why It's called as Markup Language ?**
* By using HTML we are not writting any logics,
only we are creating a structure.
#

## Tag

**What is tag?**
* tag is predefined word enclosed with angular braces
* in HTML 2 types of tags
    * Paired Tag
    * Unpaired tag or self closing tag

**Paired Tag?** 
* Any tag which has a openning tag and closing tags is called paired tags
    * Eg:
        `<h1>welcome</h1>`

    *Syntax* 
    * `<tagname> Content </tagname>`

**Unpaired Tag?**
* any tag that only the openning tag there no closing tag is called as unpaired tags.
    * Syntax

        `<br>,<hr>,<img>,<meta>`

## Structure of the HTML

    `
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <title>Document</title>
    </head>
    <body>
        
    </body>
    </html>
    `


**`<DOCTYPE html>`**
* It is used to tell broswer whcih version of html we aare using.
* Currently we are using html version 5.

**`<html></html>`**
* It is the root tag of html structure.
* all the content should be inside this root tag.

**`<head></head>`**
* this is used to provide the meta information

**`<title></title>`**
* This is use show the title of the page 

**`<body></body>`**
* The content we want to display in the broswer everything should be written inside this tag.

## Heading Tag

**Heading tags**

* In html for providing headlines (heading or subheading)
* There are 6 heading tags 
* `<h1></h1> to <h6></h6>`
* heading tags all paired tags
* all the heading tags are block - level element

    * Eg
        * `<h1></h1>`
        * `<h2></h2>`
        * `<h3></h3>`
        * `<h4></h4>`
        * `<h5></h5>`
        * `<h6></h6>`

**Paragraph**
* In html if we want to write a any text content , that should be written by using a paragraph tag(`<p></p>`)
* Paragraph tag is denoted by `<p></p>` and this is paired tag
* It is a block-level element 
* paragraph tag size is 16 pixels

## Formating tags 
* It is used to chnage the appearance or fomat of the text content

**`<b></b>`**
* This is used to make the content bold

**`<strong></strong>`**
* It is also use to make the content bold but this tag having **higher priority** compare to `<b></b>` tag

**`<i></i>`**
* It used to make the content in italic

**`<em><em>`**
* This is used to make the content itali same like **`<i></i>`**.

**`<u></u>`**
* This tage is used to make or provide the underline for the text content.

**`<ins></ins>`**
* it is also used to provide the underline for the text 

**`<mark></mark>`**
* it is used to provide high light for the text 

***`Important`***

**`<sup></sup>`**
* It is used to write any content at the power

**`<sub></su>`**
* it is used to write any content at the base

***`end of Important`***

**`<q></q>`**
* It is used to provide a double qoutes to the centent

**`<pre></pre>`**
* It is pre-formatted tag, inside this tag how we will
write the content it will display as it is .

**`<del></del>`**
* It is used to give strike through the text.

**`<br>`**
* It is used to to break the line 
* It help to move the content in the next line,
* It is unpaired tag

**`<hr>`**
* It is used to provide the horizontal line
* It is unpaired tag

## Elements
* Element is camination of tags and the content inside the tag

*Types of a Elements*
* We have 3 type of Element in html
    * Block Level
    * InLine Level
    * Inline-Block level 


**Block Level**
* These elements are taking the full space of its parents and it will displaying in a next line 
* By Default it will take full width of the parent 
* We can provide the *height and width* for these elements

    * Eg
        * `<div></div>`

**Inline Level**
* These Element will displaying in the same-line 
* we *can't provide height and width* 
* It Occupying the content area

    * Eg
        * `<b>,</b> | <i></i> | <u></u> | <span></span>`

**Inline_Block Levele**
* It is the combination of `inline and block level element `
* This Elements are will *display in same line but we can not provide the height and width*

    * Eg
        * `<button></button> | <input/> | <img> `

## Attribute
* Attributes are used to provide additional information to the tags.
* Attribute should be written in opening tags.
* Eg
    *Syntax*

        <tagname attributename="value"></tagname> 

### `<Img> tags`
* It is used to add the image in the webpage.
* In this tag we have 4 attributes
    1. *src* : It is used to provide the path of the image.
    2. *alt* : It is used to provide the alternate messag .
        
        * If the image is not displaying that time this alt message will displayed on the page.
    3. *height and width* : Used for resizing the image.
* `<img>` tag : It is a self closing tag / unpaired tag
* it is one *inline-block* level element.
