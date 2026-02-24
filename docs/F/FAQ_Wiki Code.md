# FAQ/Wiki Code

<center>
<br><br><br>
<span style="font-size:50px"><nowiki><!--Codes--></nowiki></span>

This document is intended to be a Quick Tutorial. Please amend this description to reflect purpose of this document.
</center>
==Sample Code==

See the following example, taken from [[Basic Bee]]; trivia section. (31 May 2018)
<pre>
==Trivia==
* This is one of the only bees without an ability (the other one being Brave Bee).
* This is the only bee that can't be obtained from [[Royal Jelly]].
** However, there used to be Basic Bee Jelly obtained by from a code called DontUseThisJelly.
** This code has expired, so you can't obtain Basic Bee Jelly anymore.
** This is most likely the first bee the player will get and discover.
*Basic Bee and [[Demo Bee]] have the same skin colors.
*Basic Bee is the only bee that can be obtained from only a [[Basic Egg]].
*Basic Bee is the only common bee.
*Basic Bee is the most common colorless bee in the game.
{{BeeNav}}
</pre>

We will be referring to this code segment in this document.


===Note on Code Segment===

This guide was originally written for mid-level players or that has a basic knowledge of wikitext.


==Preface==

Most of the codes are of a basic format. Either double "{" and closed with double "}" (curly brackets) or double "[" closed with double "]" (square brackets) or single straight quotes " ' ". Some codes from HTML 5 do support Wikia. such as '''<nowiki><center></nowiki>'''.

==Basic Formatting Codes==

Basic formatting codes are simple instructions that tell the wiki you want more than plain text in a single paragraph. =D


===Paragraphs===

The extra line between paragraphs creates a new paragraph. If the line is removed, the two paragraphs will join. ''Two empty lines'' between paragraphs increases the space between paragraphs.

A colon ":" means indent, like so:

:Indent / block paragraph.


===Lists===

The asterisk "*" at the beginning of a line (no space in front) means the wiki should insert a bullet like this:

* bullet


A "#" (hash/pound) sign means a numbered list, like so:

<pre>
# Item 1
# Item 2
</pre>

# Item 1
# Item 2


You can combine paragraph code and list code thus:

<pre>
::* Sub level
:::# Item 1, Sub 1
</pre>

::* Sub level
:::# Item 1, Sub 1

or you can add indent by adding more list code:

<pre>
* Title
**Sub-title
</pre>

*Title
**Sub-title

<pre>
#Media
##Photo
##Video
</pre>

#Media
##Photo
##Video

Inserting a space (by pressing enter) before the start of your text is recommended and improves readability in the source code.

===Italics & Boldface===

<pre>''italics''</pre> gives ''italics''.


<pre>'''bold'''</pre> gives '''bold'''.


<pre>'''''bold and italicized'''''</pre>
gives '''''bold and italicized'''''.

===Heading===
This code shows a main part of the topic such as a bee's history and trivia. Using this code creates a table of contents, which helps users to navigate throughout the page.
<pre>Normal text

==Heading 2==

===Heading 3===

====Heading 4====

=====Heading 5=====

 preformatted </pre>

The code <code><nowiki><pre></nowiki></code> can also preformat the text.

===Links===

<pre>[[Basic Bee]]</pre> gives [[Basic Bee]]. The square brackets mean you are trying to link to a page on the wiki (known as internal links). "Basic Bee" is the name of the page.

Note: If it didn't work as you expected, check your spelling and the capitalization. 

You can also change the name of the link. But it will lead you to the same page:

<pre>[[Basic Bee|Common Bee]]</pre> gives [[Basic Bee|Common Bee]].

In order to add URLs (external links), single square brackets are required instead of two.

<pre>[https://www.roblox.com]</pre> gives [https://www.roblox.com].

As you can see that it gives out number instead of the actual link. In order to solve this, you need add a name of the link. But instead of using a pipe "|" to separate it, adding a space is at least required.

<pre>[https://www.roblox.com ROBLOX]</pre> gives [https://www.roblox.com ROBLOX].

And one step closer if you want to add a Wikipedia Link:

<pre>[[Wikipedia:Bee]]</pre> gives [[Wikipedia:Bee]]

These are the basics. As you edit other work, you will learn more from other people's "codes".

===Reference Code===

This code's purpose is to show what data is gathered from another external page.

<pre>
<ref>[[Basic Bee]] Basic Bee </ref>
</pre>
gives

<ref>[[Basic Bee]] Basic Bee </ref>

and to show all summary of reference quotes:

<pre>
<references />
</pre>

gives

<references />


NOTE: These two codes must be performed or else an error will occur.


==Tables==

Sometimes we use Tables to organize and summarize data, particularly when there is large amounts of it -- e.g., for Stick Bug hp.

Code segment for Tables follow:

<pre>

 {| class="wikitable"
 |-
 ! Header 1
 ! Header 2
 ! Header 3
 |-
 | row 1, cell 1
 | row 1, cell 2
 | row 1, cell 3
 |-
 | row 2, cell 1
 | row 2, cell 2
 | row 2, cell 3
 |}

</pre>

The preceding code produces:

{| class="wikitable"
|-
! Header 1
! Header 2
! Header 3
|-
| row 1, cell 1
| row 1, cell 2
| row 1, cell 3
|-
| row 2, cell 1
| row 2, cell 2
| row 2, cell 3
|}

===Code Definitions===

'''{|''' and '''|}''' start and end tables respectively.

'''|-''' marks the beginning of a new row (a set of cells arranged in a horizontal manner.)

'''!''' marks the beginning of a new header cell (for titles - please do not use this as a lazy way to bold the contents of a cell)... Header cells may be assigned special functions, e.g., for sorting.

'''|''' ''at the beginning of a line'' is used to mark the beginning of a new cell. When this symbol is used ''elsewhere'', it may be used to separate the cell formatting from its contents. E.g., <pre>| align="center" | centered contents</pre>


[http://en.wikipedia.org/wiki/Help:Table Wikipedia's Help:Table] is a more complete in detail and includes advanced code &/ options if you need it.

==Templates==

Templates are documents written by (advanced) coders to allow Bee Swarm Simulator Wiki to have a consistent look throughout. The curly brackets really mean "insert this document here, with the following conditions." 

===Tabbers===

Wikia has an extension called ''"Tabber"''. They give content and title on every tab; the purpose is to make the wiki more organized and more designed.
====<big>Content Tabbers</big>====
Content Tabbers are type of tabbers that require to write information inside the same page. The Content Tabber uses section headers as pseudo-links to open and navigate through the tabs.

<pre>
<tabber>
Colors=
Red, Blue, Colorless
|-|
Hats=
Helmet, Propeller Hat, Beekeeper's Mask
</tabber>
</pre>

gives

<tabber>
Colors=
Red, Blue, Colorless
|-|
Hats=
Helmet, Propeller Hat, Beekeeper's Mask
</tabber>

====<big>Tab Viewers</big>====
Unlike Content Tabbers, Tab Viewers just view the page contents. They require less space to configure the tabber. In order to edit the content, you need to edit it to the page where it projects it.
<pre>
<tabview>
Scooper|Page 1||
Pouch|Page 2||
Backpack|Page 3||
</tabview></pre>

gives

<tabview>
Scooper|Page 1||
Pouch|Page 2||
Backpack|Page 3||
</tabview>
<hr>
There are three parts of the tab viewer:
* The actual link of the page,
* Name projected and,
* The pipe.

The pipe separates the text. Add a pipe "|" to separate the link and the name, while two pipes "||" to separate the tabs.

Like for example, if something is wrong about Page 2, you need to go to [[Tab View 2]] page.
===Template ''"Bee"''===

''Main Page:''[[Template:Bee]]

===Template ''"Bear"''===

''Main Page:''[[Template:Bear]]
{{Bear/doc}}

===Notice Templates ===
Templates are used for giving notices above the page content. These templates do not require to fill-up information.
* Template Stub
: Stubs are used when a section of the page is partially finished or not yet added.

<pre>
{{Stub}}
</pre>

*Template RemovedContent
: The following page is permanently removed in the game.

<pre>
{{RemovedContent}}
</pre>

*Template Delete
:This template's purpose is to mark a '''warning''' or a notice that the page is about to be deleted. Simply put the code<pre>{{Delete}}</pre>
to use the template.

===Navigation Templates===
Templates are used for giving list of pages that are related to the visited page. Navboxes are usually located at the bottom of the article page.
* BeeNav
: All Bee pages and their images are listed here.

<pre>
{{BeeNav}}
</pre>
* BearNav
: All Bear pages are listed here.

<pre>
{{BearNav}}
</pre>
* MapNav
: All locations of the game and their pages are listed here.

<pre>
{{MapNav}}
</pre>
* CurrencyNav
: In-game currencies are listed here.

<pre>
{{CurrencyNav}}
</pre>
* Items
: All In-game items are listed here.

<pre>
{{Items}}
</pre>
[[Category:Guides]]