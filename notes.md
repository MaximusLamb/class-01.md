
# Structure
```html
The lower the number when using is the higher level of the heading. would be a sub heading and <h3> would be a sub heading of<h1>

Inside of headings you can use <p> to signify a paragraph.
```    
# Brackets and Attributes
Inside of a bracket before the second "carrot" is where you put your attributes.  After the attributes you put a "=" and set your attribute values.
        The most common way to set up for an html is to put a title inside of a head and beneath the head put the body of your work.
  

# Extra Markups

```html
To add a comment to your code that will not be visible in your browser put the wording in between <"!-- -->

The <id> attribute is used to uniquely identify that element from other elements on the page.

The <class> attribute is used uniquely identify **Multiple** elements.

The <div> element allows you to group a set of elements together in one block-level box. Div elements can be used to contain all of the elements for the headers
on your site.  

Using an id or class element attribute inside of the div element means you can create css style rules to indicate how much space the div element should occupy
on the screen. And you can change all the elements of the div contained within the certain div.

The <span> element acts like an inline equivalent of the div element.  The most common reason why people use span elements is so that they can control the appearance
of the content of these elements using CSS.
    
<iframe> An iframe is like a little window that has been cut ino your page and in that window you can see another page.
        
<src> 
    the src attribute specifies the URL of the page to show in the frame

 <height> the height attribute specifies the height of the iframe in pixels.

 <width> the width attribute specifies the width of the iframe in pixels

 <scrolling> the scrolling it indicates whether the iframe should have scrollbars or not.

 <frameborder> it indicates whether the frame should have a border or not.

<seamless> the seamless attribute does not need a value, but you will often see authors give it a value of seamless.
        
 <meta> the meta lives inside the <head> element and contains information about that web page.
        
<description> this contains a description of the page.

<keywords> This contains a list of comma-seperated words that a user might search on to find the page.

<robots> This indicates whether search engines should add this page to their search results or not.

<author> This defines the author of the web page.

<pragma> This prevents the browser from caching the page.

<expires> Because browsers often cache the content of a page.
 ```         

# HTML5 Layout

```html
<nav> 
    The nav element is used to contain the major navigational blocks on the site navigation.

<article> 
    The article element acts as a container for any section of a page that could stand alone and potentially be syndicated.

<aside>
     The aside element has two purposes, depending on whether it is inside an article element or not.

<section> 
    The section element groups related content together, and typically each section would have its own heading.

<hgroup> 
    The purpose of the hgroup element is to group together a set of one or morthrough h6 elements so that they are treated as one single heading.

<figure>/<figcaption> 
    The figure element should also contain a figcaption element which provides a text description for the content of the figure element.

``` 
## Linking Around Block level elements
```html
    Web page authors to place an <a> element around a block level element that contains child elements.  Ths allows you to turn an entire block into a link.
```
## Process & Design
```html
Every Website should be designed for the target audience, not just for yourself or the site owner.  It is therefore very important to understand who your target audence is.
```

## Target Audience
    
* What is the age range of your target audience?
* Will your site appeal to more women or men? What is the mix?
* Which country do your visitors live in?
* Do they live in urban or rural areas?
* What is the average income of visitors?
* What level of education do they have
* What is their marital or family status?
* What is their occupation?
* How many hours do they work per week?
* How often do they use the web?
* What kind of device do they use to access the web?
* What is the size of the company or relevant department?
* What is the position of people in the company who visit your site?
* Will visitors be using the site for themselves or for someone else?
* How large is the budget they control?

# JavaScript

## Start With The Big Picture

### Define The Goal
* First you need to define the task you want to achieve.

### Design The Script
* To design a script you split the goal out into a series of tasks that are going to be involved in solving this puzzle.

### Code Each Step
* Each of the steps needs to be written in a programming language that the computer understands.

## Objects (Things)
* In computer programming, each physical thing in the world can be represented as an **object**.

### Each object can have its own:
* Properties
* Events
* Methods

## Methods

### What is a method?
* Methods typically represent how people {or other things} interact with an object in the real world.
* They tell you something about that object (using information stored in its properties.)
* Change the value of one or more of that object's properties.
### What does a method do?
* The code for a method can contain lots of instructions that together represent one task.
* When using a method, you do not always need to know *how* it achieves its task; you just need to know how to ask the question and how to interpret any answers it gives you.

## Document Objects
### Properties
* Properties describe characteristics of the current web page (such as the title of the page)
### Methods
* Methods perform tasks associated with the document currently loaded in the browser (such as getting information from a specified element or adding new content.)
### Events
* You can respond to events, such as a user clicking or tapping on an element.

## How a Browser sees a web page
1. **Revieve a page as HTML code**
* Each page on a website can be seen as a seperate document.  So the web consists of many sites, each made up of one or more documents.

2. **Create a Model Of the Page and Store it in Memory**
* The model shown on the right hand page is a representation of one very basic page.  Its structure is reminiscent of a family tree. At the top of the model is a **Document Object**, which represents the whole document.

3. **Use a Rendering Engine to Show the Page on Screen**
* If there is no CSS, the rendering engine will apply default styles to HTML elements.  However, the HTML code for this example links to a CSS style sheet, so the browser requests that file and displays the page accordingly.