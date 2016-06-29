---
layout: page
title: Theme Styles
---

## Full Style Test

Below is just about everything you’ll need to style in the theme. Check the source code to see the many embedded elements within paragraphs.

* * *

# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

* * *
<abbr title="Hyper Text Markup Language">HTML</abbr> and <abbr title="Cascading Style Sheets">CSS</abbr> are our tools for styling. 

Use square braces and parentheses to form links in markdown:  [test link](# "test link").
Put words into a pair of two asterisks to make them appear bold: **This is strong.** N
To make words look italicized, put them between a pair of underscores will do that: _This is emphasized._ 
Making super scripts and sub scripts is also easy. Use the sup and sub tags around the characters you wish to super or sub script: 5<sup>3</sup> = 125\. Water is H<sub>2</sub>O. 
Citations are just as easy with use of the cite tag. <cite>The New York Times</cite> (That’s a citation).

By using text decoration styles you do things like:
Underlining text: <span style="text-decoration:underline;">Underline.</span> 
Stricking through text: This <span style="text-decoration:line-through;">text</span> has been struck.

Struck out text can also be done via the del and ins html tags. i.e. <del>Dinner’s at 5:00.</del> <ins>Let’s make that 7.</ins> 

To copy a file type `COPY undefined`. 

* * *

## Media

This is an example of how various forms of media will appear on this website

### Big Image

This is how large images will appear on this website.  

![Test Image](http://www.ddl.kr/data/file/gallery/3554530584_TyJ2waAV_a0e582c316335ac1b8701f188ff974ab4a23583c.jpg)

A wonderful photo of green grapes.  

### Small Image

Here is an example of how small images will appear on this website.  

![Small Test Image](https://c4.staticflickr.com/7/6126/5996465579_df36dbdd23_n.jpg)

Creative Commons small image.  

* * *

## List Types

### Definition List

<dl>

<dt>Definition List Title</dt>

<dd>This is a definition list division.</dd>

<dt>Definition</dt>

<dd>An exact statement or description of the nature, scope, or meaning of something: _our definition of what constitutes poetry._</dd>

</dl>

### Ordered List

1.  List Item 1
2.  List Item 2

    1.  Nested list item A
    2.  Nested list item B
3.  List Item 3

### Unordered List

*   List Item 1
*   List Item 2
    *   Nested list item A
    *   Nested list item B
*   List Item 3

* * *

## Table

<table>

<tbody>

<tr>

<th>Table Header 1</th>

<th>Table Header 2</th>

<th>Table Header 3</th>

</tr>

<tr>

<td>Division 1</td>

<td>Division 2</td>

<td>Division 3</td>

</tr>

<tr class="even">

<td>Division 1</td>

<td>Division 2</td>

<td>Division 3</td>

</tr>

<tr>

<td>Division 1</td>

<td>Division 2</td>

<td>Division 3</td>

</tr>

</tbody>

</table>

* * *

## Preformatted Text

Typographically, preformatted text is not the same thing as code. Sometimes, a faithful execution of the text requires preformatted text that may not have anything to do with code. Most browsers use Courier and that’s a good default — with one slight adjustment, Courier 10 Pitch over regular Courier for Linux users.

### Code

Code can be presented inline, like `<?php bloginfo('stylesheet_url'); ?>`, or within a `<pre>` block.

CSS code

```css
#container {
    float: left;
    margin: 0 -240px 0 0;
    width: 100%;
}
```

Ruby code

```ruby
class Song
  def initialize(title, artist, album)
    @title  = name
    @artist = artist
    @album  = album
  end
end

class InstrumentalSong < Song
  def initialize(name, artist, album, lyrics)
    super(name, artist, album)
    @lyrics = lyrics
  end
end
```

## Blockquotes

Let’s keep it simple. Italics are good to help set it off from the body text. Be sure to style the citation.

> Good afternoon, gentlemen. I am a HAL 9000 computer. I became operational at the H.A.L. plant in Urbana, Illinois on the 12th of January 1992\. My instructor was Mr. Langley, and he taught me to sing a song. If you’d like to hear it I can sing it for you. <cite>— [HAL 9000](http://en.wikipedia.org/wiki/HAL_9000)</cite>

And here’s a bit of trailing text.

* * *

## Text-level semantics

The [a element](#) example
The <abbr>abbr element</abbr> and <abbr title="Title text">abbr element with title</abbr> examples
The **b element** example
The <cite>cite element</cite> example
The `code element` example
The <del>del element</del> example
The <dfn>dfn element</dfn> and <dfn title="Title text">dfn element with title</dfn> examples
The _em element_ example
The _i element_ example
The <ins>ins element</ins> example
The <kbd>kbd element</kbd> example
The <mark>mark element</mark> example
The <q>q element <q>inside</q> a q element</q> example
The <s>s element</s> example
The <samp>samp element</samp> example
The <small>small element</small> example
The <span>span element</span> example
The **strong element** example
The <sub>sub element</sub> example
The <sup>sup element</sup> example
The <var>var element</var> example
The <u>u element</u> example

* * *

## Embeds

Sometimes all you want to do is embed a little love from another location and set your post alive.

### Video

Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

<iframe src="//player.vimeo.com/video/83910533?title=0&amp;byline=0&amp;portrait=0" width="600" height="338" frameborder="0" webkitallowfullscreen="" mozallowfullscreen="" allowfullscreen=""></iframe>

Culpa qui officia deserunt mollit anim id est laborum.

### Slides

Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

<div><iframe class="speakerdeck-iframe" frameborder="0" src="//speakerdeck.com/player/88f09170c0e60131e0fe72c781b73270?" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true" style="border: 0px; margin: 0px; padding: 0px; border-radius: 5px; width: 710px; height: 461.37499999999955px; background: transparent;"></iframe></div>

Culpa qui officia deserunt mollit anim id est laborum.

### Audio

Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

<iframe width="100%" height="450" scrolling="no" frameborder="no" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/202156472&amp;auto_play=false&amp;hide_related=false&amp;show_comments=true&amp;show_user=true&amp;show_reposts=false&amp;visual=true"></iframe>

Culpa qui officia deserunt mollit anim id est laborum.

### Code

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt.

<div><iframe id="cp_embed_bcqhe" src="//codepen.io/brenden/embed/VLjKMQ/?height=268&amp;theme-id=0&amp;slug-hash=bcqhe&amp;default-tab=result&amp;user=brenden" scrolling="no" frameborder="0" height="268" allowtransparency="true" allowfullscreen="true" class="cp_embed_iframe undefined" style="width: 100%; overflow: hidden;"></iframe></div>

It is awesome.

<small>Source: Markdown code of this page is based on Ghost's [comprehensive style test](http://demo.ghost.io/style-test/)</small>