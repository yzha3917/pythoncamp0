# Markdown Introduction


### 1. What is markdown ? 

Markdown is both an open markup language that editting plain text files into formatted styles and the the name of the tool to achive this process. The filename extensions is '.markdown' or '.md' in short. 

This language is originally developed by John Gruber, and initially released in 25th March, 2004. According to the [Readme file](http://daringfireball.net/projects/markdown/), the goal is to enable people 
> to write using an easy-to-read, easy-to-write plain text format, and optionally convert it to structurally valid XHTML (or HTML)

### 2. Why should I choose markdown ? 

##### 2.1. WYSIWYG
Comparing to WYSIWYG (what you see is what you get) word procossers, such as Word, both structure and content are mixed up at the same time. Therefore, writers have to generate contents, as well as focusing on editting formats. 

##### 2.2. WHSIWYM
On the other hand, troditional WYSIWYM (what you see is what you mean) editors, taking LaTeX as an example, allow the users to focus on the structure first, and then worry about riching up the skeleton. However, the super complex syntax is really a stretch for the beginners to start up. Meanwhile, the fineness and accuary brought by LaTeX are certainly unnecessary for daily purposes.

##### 2.3. Markdown
As a light editing language, markdown eases the burden of formatting by introducing easy-to-remember syntax system, which enables users to concentrate on writing itself with minimum effort. 


### 3. Standard syntax <sup>1</sup>

##### Strong and Emphasize
    *emphasize*   **strong**
    _emphasize_   __strong__

##### Links and Email
Inline:

	An [example](http://url.com/ "Title")
Reference-style labels (titles are optional):

	An [example][id]. Then, anywhere
	else in the doc, define the link:

  [id]: http://example.com/  "Title"
##### Email:

	An email <example@example.com> link.
	Images
Inline (titles are optional):

	![alt text](/path/img.jpg "Title")
##### Reference-style:

	![alt text][id]

	[id]: /url/to/img.jpg "Title"
	
##### Headers

Setext-style:

	Header 1
	========

	Header 2
	--------
atx-style (closing #’s are optional):

	# Header 1 #

	## Header 2 ##

	###### Header 6
##### Lists
Ordered, without paragraphs:

	1.  Foo
	2.  Bar
Unordered, with paragraphs:

	*   A list item.

    	With multiple paragraphs.

	*   Bar
You can nest them:

	*   Abacus
	    * answer
	*   Bubbles
 	    1.  bunk
	    2.  bupkis
	        * BELITTLER
	    3. burper
	*   Cunning
##### Blockquotes
	> Email-style angle brackets
	> are used for blockquotes.

	> > And, they can be nested.

	> #### Headers in blockquotes
	> 
	> * You can quote a list.
	> * Etc.
##### Inline Code
	`<code>` spans are delimited
	by backticks.

	You can include literal backticks
	like `` `this` ``.
##### Block Code
Indent every line of a code block by at least 4 spaces or 1 tab.

	This is a normal paragraph.

  	    This is a preformatted
  	    code block.
##### Horizontal Rules
Three or more dashes or asterisks:

	---

	* * *

	- - - - 
##### Hard Line Breaks
End a line with two or more spaces:

	Roses are red,   
	Violets are blue.
	
##### Tables 
Colons can be used to align columns.

	| Tables        | Are           | Cool  |
	| ------------- |:-------------:| -----:|
	| col 3 is      | right-aligned | $1600 |
	| col 2 is      | centered      |   $12 |
	| zebra stripes | are neat      |    $1 |

The outer pipes (|) are optional, and you don't need to make the raw Markdown line up prettily. You can also use inline Markdown.

	Markdown | Less | Pretty
	--- | --- | ---
	*Still* | `renders` | **nicely**
	1 | 2 | 3
### 4. Variants

Because of the open licence nature of markdown, and the absence of universal syntax system when it was firstly introduced, the fragmentation phenomenon was and still is probmatic. Attempts, including [CommonMark](http://commonmark.org/), [MultiMarkdown](http://fletcherpenney.net/multimarkdown), and other implements, remain partially success. For instance, popular sites such as GitHub<sup>2</sup>, reddit, Stack Exchange use variants of Markdown. 


-----
<1> [Markdown Cheetsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)  
<2> [GitHub Flavored Markdown](https://help.github.com/articles/github-flavored-markdown/)


