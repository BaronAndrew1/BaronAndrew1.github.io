<!--Content from site -->

## `<html>`

the main enchilada, the whole `document`, that which wraps all the others... except for [`<!DOCTYPE>`](#doctype), for some reason.

* _parents_: none, it's the top
* _content_: _only_ [`<head>`](#head) and [`<body>`](#body)
* _display_: `block`, maybe? I mean, I can see it... RESEARCH!

### Attributes

* `class` -- a space-separated list of category names
* . . .

. . .

## `<div>`

A generic page division that should only be used if no other, more semantic choice is appropriate.

* _parents_: anything that accepts [Flow Content][1], which is apparently a lot of things.
* _content_: any [Flow Contant][1], palpable content (WTF?)
* _display_: `block`

. . .

###### Footnotes

[1](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/Content_categories#Flow_content)

<!--Self Created Content-->

## '<!DOCTYPE>'

A version declaration for html format documents.  Mainly used for SGML/HTML4.01.  This tag informs the browser which version you are using allowing it to render correctly.

## '<!-- -->'

Determines the use of a comment seen only by coders.  Used to notify other programmers or yourself about the contents of the code below.

## 'html'

Encompasses the whole document.  Tells the computer and any programmers that the information within is in html formatting.

_parents_: none

_content_: _Only_ ['<head>'](#head) and ['<body>'](#body).

_display_: `block`

## 'head'

Encompasses elements of the program not necessarily visible to use user.  These include the title and image on the task bar.  Metadata tends to be placed here.

_parents_: `html`

_content_:

_display_: `block`

## 'body'

The bulk of all written code goes here.  This holds all the information on the web page seen by users.

_parents_: `html`

_content_:

_display_: `block`

## 'title'

Defines the title and can only hold text.

_parents_: `head`

_content_: `text`

_display_: `block` (Really, I am not sure about this??)

## 'article'

A reusable self contained composition. (a complete document meant to be reusable or relocated at any time.)

_parents_:  any flow content other than `address`.

_content_:  any [flow content][1] [sectioning content][1] or [palpable content][1].

_display_:  `block`

## 'address'

Provides location information for the article or body in which its embedded.

_parents_:  any element that accepts [flow content][1]

_content_:  [flow content][1] not including `article` [heading content][1] [sectioning content][1] `heading` or `footing`

_display_:  `block`

## 'p'

"paragraph".  This contains most standard text used in the document.

_parents_:  any element that accepts [flow content][1]

_content_:  phrasing content (text and text markups)

_display_:  `block`

## 'div'

A generic page division.

_parents_:  anything that accepts [flow content][1]

_content_:  [flow content][1]

_display_:  `block`

## 'span'

Generic inline container.

_parents_:  any element that accept [flow content][1] and [phrasing content][1]

_content_:  [phrasing content][1]

_display_:  `inline`

## 'img'

Displays html image elements.

_parents_:  any element that accepts embedded content.

_content_:  empty element.

_display_:  `inline`

## 'picture'

_parents_:  any element that allows embedded content.

_content_:  zero or more source elements followed by an img.

_display_:  `block`
