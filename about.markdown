---
layout: page
title: About this site
permalink: /about/
---

Try making a change in markdown file on github.com. What happens when commit?

Here's a bit of added text. What does it do? Try playing with markdown formatting...

looked up here: https://kramdown.gettalong.org/quickref.html

how to make a hyperlink? thing to click in square brackets, actual link in parentheses
[hyperlink1](https://kramdown.gettalong.org/quickref.html)

Here is using a hash #this stuff and a hash on either end #this stuff# and after a carriage return
#some stuff
preceded by 2 carriage returns


#stuff again

after carriage return, over hyphens
---------

after carriage return/blank line, over equals sign
=

after carriage return over underscores
_________
Here is using an asterix on either end *that stuff* and 2 on either end **two**
and three ***three***

* one
* two
* three - need to have a space after the asterisk


definition list
: one thing
: two thing no idea how to make this work
   : three
   :   four


definition term
: This definition will just be text because it would normally be a
  paragraph and the there is no preceding blank line.

  > although the definition contains other block-level elements

: This definition *will* be a paragraph since it is preceded by a
  blank line.

  ok I give up on that

  | A simple | table |
| with multiple | lines|

**a fancy table**

| Header1 | Header2 | Header3 |
|:--------|:-------:|--------:|
| cell1   | cell2   | cell3   |
| cell4   | cell5   | cell6   |
|----
| cell1   | cell2   | cell3   |
| cell4   | cell5   | cell6   |
|=====
| Foot1   | Foot2   | Foot3
{: rules="groups"}



This is <span style="color: red">written in
red using html tags</span>.
This is *red using inline tags*{: style="color: red"}.

how to add an image? supposed to be similar to adding a hyperlink, but not working.
Does image need to be saved locally? If so, where?

maybe see something like this: https://www.xaprb.com/blog/how-to-style-images-with-markdown/  or like this https://html.com/attributes/img-src/

An image: ![meow](https://commons.wikimedia.org/wiki/Category:Felis_silvestris_catus#/media/File:Pumiforme.JPG)

another try: ![meow](https://unsplash.com/photos/INw1KTFtDpI)
another try: ![meow](/testphoto.jfif)


straight html with formatting and title and alt:
<img src="https://commons.wikimedia.org/wiki/Category:Felis_silvestris_catus#/media/File:Pumiforme.JPG" alt="Kitten" title="A cute kitten" width="150" height="100" />

<img src="https://commons.wikimedia.org/wiki/Category:Felis_silvestris_catus#/media/File:Pumiforme.JPG">

 I don't see the difference in the URLS that makes one work but not the other.
 Will need to look at how DG added photos in his website.

here's trying without any kind of caption or formatting or anything, just html
<img src="https://upload.wikimedia.org/wikipedia/commons/f/f9/Phoenicopterus_ruber_in_S%C3%A3o_Paulo_Zoo.jpg">

<img src="https://upload.wikimedia.org/wikipedia/commons/f/f9/Phoenicopterus_ruber_in_S%C3%A3o_Paulo_Zoo.jpg" alt="altbird" title="bird"  width="150" height="100">

<img src="https://upload.wikimedia.org/wikipedia/commons/f/f9/Phoenicopterus_ruber_in_S%C3%A3o_Paulo_Zoo.jpg" alt="altbird" title="bird"  width="150" height="100"/>


This is a text with a
footnote[^1].

[^1]: And here is the definition. It was originally written directly below the reference.


This is the base Jekyll theme. You can find out more info about customizing your Jekyll theme, as well as basic Jekyll usage documentation at [jekyllrb.com](https://jekyllrb.com/) Trying a second footnote [^2].

[^2]: here is the second footnote.


You can find the source code for Minima at GitHub:
[jekyll][jekyll-organization] /
[minima](https://github.com/jekyll/minima)

You can find the source code for Jekyll at GitHub:
[jekyll][jekyll-organization] /
[jekyll](https://github.com/jekyll/jekyll)


[jekyll-organization]: https://github.com/jekyll
