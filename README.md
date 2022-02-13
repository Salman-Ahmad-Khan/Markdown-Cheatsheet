# Markdown-Cheatsheet
```Link```
[The Ultimate Markdown Cheat Sheet]https://github.com/Salman-Ahmad-Khan/Markdown-Cheatsheet/blob/master/README.md)


<!-- 
 What is Markdown? Markdown is a way of writing rich-text (formatted text) content using plain text formatting syntax. From this post, you’ll learn all the Markdown’s major commands that will help you create an awesome GitHub README. I’ll talk about the 11 most commonly used markdown topics. I’ve also mentioned different ways, such as using HTML tags to style your README. If you’re interested, you can have a look at the HTML whitelists on GitHub.
You can download everything I’ve discussed in this post from my GitHub repository. Below I have got a table of content so that you can easily navigate through this post.
· Headings
· Text styles
· Syntax Highlighting
· Alignments
· Tables
· Links
· Images
· Lists
· Horizontal Rule
· Miscellaneous
· Bitbucket
· Tools
Headings
There are few options to create headings. We can use Markdown or HTML or an alternative syntax to create our desired headings.
First, let’s talk about the markdown syntax.
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
The second option, using the HTML syntax.
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
Finally, we can use an alternate syntax. This method only works for heading 1 and heading 2. Add any number of = or - below the text for heading 1 or heading 2.
Heading 1
=
Heading 2
-
Now, let’s see how it looks on GitHub.
Headings
Headings
Text styles
Using markdown syntax, we can change texts’ styles, including bold, italic, blockquotes, monospaced, underlined, strike-through, boxed, subscript, and superscript.
We can use two asterisks (**), underscores (__), or an HTML tag <strong> to make a text bold. To make text italic, we can use one asterisk (*), underscore (_), or an HTML tag <em>. Also, we can make the text bold and italic at the same time.
Bold
**The quick brown fox jumps over the lazy dog.**
__The quick brown fox jumps over the lazy dog.__
<strong>The quick brown fox jumps over the lazy dog.</strong>
Italic
*The quick brown fox jumps over the lazy dog.*
_The quick brown fox jumps over the lazy dog._
<em>The quick brown fox jumps over the lazy dog.</em>
Bold and Italic
**_The quick brown fox jumps over the lazy dog._**
<strong><em>The quick brown fox jumps over the lazy dog.</em></strong>
Now, let’s see how it looks on GitHub.



Bold and Italic text styles
To create blockquote, we can use the greater than sign >. We can create a single-line or multi-line blockquote. Also, blockquote inside a blockquote. We can add other text styles inside a blockquote, such as bold or italic text styles.
Blockquotes
> The quick brown fox jumps over the lazy dog.
> The quick brown fox jumps over the lazy dog.
> 
> The quick brown fox jumps over the lazy dog.
> 
> The quick brown fox jumps over the lazy dog.
> The quick brown fox jumps over the lazy dog.
>> The quick brown fox jumps over the lazy dog.
>>> The quick brown fox jumps over the lazy dog.
> **The quick brown fox** *jumps over the lazy dog.*
Now, let’s see how it looks on GitHub.

Blockquotes text styles
We can achieve monospaced, and underlined styles using HTML tags <samp> and <ins>. For a strike-through style, we can use two tilda sign ~~.
Monospaced
<samp>The quick brown fox jumps over the lazy dog.</samp>

Underlined
<ins>The quick brown fox jumps over the lazy dog.</ins>

Strike-through
~~The quick brown fox jumps over the lazy dog.~~
Now, let’s see how it looks on GitHub.



Monospaced, Underlined, and Strike-through text styles
We can use an HTML <table> tag to create a box.
Boxed
<table><tr><td>The quick brown fox jumps over the lazy dog.</td></tr></table>
Now, let’s see how it looks on GitHub.

Boxed text style
We can achieve subscript and superscript styles using HTML tag <sub> and <sup>. It is useful when you’re writing a mathematical formula.
Subscript <sub>The quick brown fox jumps over the lazy dog.</sub>
Superscript <sup>The quick brown fox jumps over the lazy dog.</sup>
Now, let’s see how it looks on GitHub.
Subscript and Superscript text styles
Subscript and Superscript text styles
Syntax Highlighting
We can use a single backtick ` before and after the code block to create the following view.
A class method is an instance method of the class object. When a new class is created, an object of type `Class` is initialized and assigned to a global constant (Mobile in this case).
As you can see the word Class is highlighted.
Code Highlighting
Code Highlighting
We can also use triple backticks ``` before and after the code block to create the following view.
```
public static String monthNames[] = {"January", "February", "March", "April", "May", "June", "July", "August", "September", "October", "November", "December"};
```
Code Highlighting
Code Highlighting
We can add an optional language identifier to enable syntax highlighting. Refer to this and this GitHub documents to find all the valid keywords.
```java
public static String monthNames[] = {"January", "February", "March", "April", "May", "June", "July", "August", "September", "October", "November", "December"};
```
Now, let’s see how it looks on GitHub.
Syntax Highlighting
Syntax Highlighting
Alignments
By using HTML tags, we can align README contents.
<p align="left">
<img src="https://images.unsplash.com/photo-1415604934674-561df9abf539?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=2772&q=80" width="100" height="100" border="10"/>
</p>
Left align
Left align
<p align="center">
<img src="https://images.unsplash.com/photo-1415604934674-561df9abf539?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=2772&q=80" width="100" height="100" border="10"/>
</p>
Center align
Center align
<p align="right">
<img src="https://images.unsplash.com/photo-1415604934674-561df9abf539?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=2772&q=80" width="100" height="100" border="10"/>
</p>
Right align
Right align
Now, let’s align a text.
<h3 align="center"> My latest Medium posts </h3>
Center align
Center align
Tables
Let’s create a table without headers.
<table>
<tr>
<td width="33%">
The quick brown fox jumps over the lazy dog.
</td>
<td width="33%">
The quick brown fox jumps over the lazy dog.
</td>
<td width="33%">
The quick brown fox jumps over the lazy dog.
</td>
</tr>
</table>

Table without header
To create a table with headers we need to use dashes to separate each header cell and use pipes to separate columns. The outer pipes are optional. We can use any number of dashes and spaces to increase readability. We can use colons to align columns. For left-align text, use a colon to the left of dashes. For center-align text, use a colon on both sides of dashes. For right-align text, use a colon to the right of dashes. By default Left align is used.
| Default | Left align | Center align | Right align |
| - | :- | :-: | -: |
| 9999999999 | 9999999999 | 9999999999 | 9999999999 |
| 999999999 | 999999999 | 999999999 | 999999999 |
| 99999999 | 99999999 | 99999999 | 99999999 |
| 9999999 | 9999999 | 9999999 | 9999999 |
| Default    | Left align | Center align | Right align |
| ---------- | :--------- | :----------: | ----------: |
| 9999999999 | 9999999999 | 9999999999   | 9999999999  |
| 999999999  | 999999999  | 999999999    | 999999999   |
| 99999999   | 99999999   | 99999999     | 99999999    |
| 9999999    | 9999999    | 9999999      | 9999999     |
Default    | Left align | Center align | Right align
---------- | :--------- | :----------: | ----------:
9999999999 | 9999999999 | 9999999999   | 9999999999 
999999999  | 999999999  | 999999999    | 999999999  
99999999   | 99999999   | 99999999     | 99999999   
9999999    | 9999999    | 9999999      | 9999999

Table with different alignments
Now display two tables side by side.
<table>
<tr>
<th>Heading 1</th>
<th>Heading 2</th>
</tr>
<tr>

<td>

| A | B | C |
|--|--|--|
| 1 | 2 | 3 |

</td><td>

| A | B | C |
|--|--|--|
| 1 | 2 | 3 |

</td></tr> </table>
Display two tables side by side
Display two tables side by side
Let’s create a table with multiple lines using the HTML <br/> tag.
| A | B | C |
|---|---|---|
| 1 | 2 | 3 <br/> 4 <br/> 5 |
A table with multiple lines
A table with multiple lines
Links
We can create a link in four ways. The first one is by using an inline style. The second one uses reference style, the third one using relative links, and finally auto links.
[The-Ultimate-Markdown-Cheat-Sheet https://github.com/Salman-Ahmad-Khan/Markdown-Cheatsheet/blob/master/README.md)
Inline-style
Inline-style
If you’re using the same link more the once, then using the reference style would be beneficial since you don’t have to write the link every time, and also, it’s easy to update the link. Moreover, you can use numbers for the reference text. Also, you can use the reference text as the link text.
[The-Ultimate-Markdown-Cheat-Sheet][reference text]
[The-Ultimate-Markdown-Cheat-Sheet][1]
[Markdown-Cheat-Sheet]
[reference text]: https://github.com/Salman-Ahmad-Khan/Markdown-Cheatsheet/edit/master/README.md
[1]: https://github.com/Salman-Ahmad-Khan/Markdown-Cheatsheet/edit/master/README.md
[Markdown-Cheat-Sheet]: https://github.com/Salman-Ahmad-Khan/Markdown-Cheatsheet/edit/master/README.md
Three variations of reference-style
Three variations of reference-style
We can also create relative links with all relative link operands, such as ./ and ../.
[Example of a relative link](rl.md)
Example of a relative link
Example of a relative link
GitHub can automatically create links from standard URLs.
Visit https://github.com/
Auto link
Auto link
Images
We can add images using the similar techniques we used for links.
![alt text](https://images.unsplash.com/photo-1415604934674-561df9abf539?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=100&q=80)
Inline-style
Inline-style
![alt text][image]
[image]: https://images.unsplash.com/photo-1415604934674-561df9abf539?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=100&q=80

Reference-style
Also, we can use the HTML img tag to add an image.
<img src="https://images.unsplash.com/photo-1415604934674-561df9abf539?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=2772&q=80" width="100" height="100" border="10"/>
img tag
img tag
We can also embed GIF and SVG.
<img src="https://media.giphy.com/media/qLHzYjlA2FW8g/giphy.gif" />

GIF
<img src="https://img.shields.io/badge/theultimatemarkdowncheatsheet-brightgreen.svg" />
SVG
SVG
Lists
For lists, we can have ordered and unordered lists.
1. One
2. Two
3. Three
An ordered list
An ordered list
Now let’s create an ordered list with sub-items.
1. First level
    1. Second level
        - Third level
            - Fourth level
2. First level
    1. Second level
3. First level
    1. Second level
An ordered list with sub-items
An ordered list with sub-items
To create an unordered list, we can asterisk, plus, or minus sign.
* 1
* 2
* 3
+ 1
+ 2
+ 3
- 1
- 2
- 3
Unordered lists
Unordered lists
Now let’s create an unordered list with sub-items.
- First level
    - Second level
        - Third level
            - Fourth level
- First level
    - Second level
- First level
    - Second level
An unordered list with sub-items
An unordered list with sub-items
We can also use HTML to create a list.
<ul>
<li>First item</li>
<li>Second item</li>
<li>Third item</li>
<li>Fourth item</li>
</ul>
A list using HTML
A list using HTML
Now let’s create a task list. We can create a task list using a hyphen followed by [ ], and to mark a task complete, put an x inside the brackets.
- [x] Fix Bug 223
- [ ] Add Feature 33
- [ ] Add unit tests
Task list
Tasklist
Horizontal Rule
We can use three hyphens, asterisks, or underscores to create a horizontal line.
---
***
___
Horizontal Rule
Horizontal Rule
Miscellaneous
We can include comments inside a .md file.
<!--
Lorem ipsum dolor sit amet
-->
We can use a backslash to escape literal characters. Before escaping.
*   Asterisk
\   Backslash
`   Backtick
{}  Curly braces
.   Dot
!   Exclamation mark
#   Hash symbol
-   Hyphen symbol
()  Parentheses
+   Plus symbol
[]  Square brackets
_   Underscore
Before escaping
Before escaping
After escaping.
\*   Asterisk
\\   Backslash
\`   Backtick
\{}  Curly braces
\.   Dot
\!   Exclamation mark
\#   Hash symbol
\-   Hyphen symbol
\()  Parentheses
\+   Plus symbol
\[]  Square brackets
\_   Underscore
After escaping
After escaping
We can also include emojis in our .md file.
:octocat:
-->

# Headings

```
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
```

# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5

```
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
```

<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>

Heading 1
=
Heading 2
-

# Text styles

```
Bold
**The quick brown fox jumps over the lazy dog.**
__The quick brown fox jumps over the lazy dog.__
<strong>The quick brown fox jumps over the lazy dog.</strong>
Italic
*The quick brown fox jumps over the lazy dog.*
_The quick brown fox jumps over the lazy dog._
<em>The quick brown fox jumps over the lazy dog.</em>
Bold and Italic
**_The quick brown fox jumps over the lazy dog._**
<strong><em>The quick brown fox jumps over the lazy dog.</em></strong>
```

The quick brown fox jumps over the lazy dog.

Bold

**The quick brown fox jumps over the lazy dog.**

__The quick brown fox jumps over the lazy dog.__

<strong>The quick brown fox jumps over the lazy dog.</strong>


Italic

*The quick brown fox jumps over the lazy dog.*

_The quick brown fox jumps over the lazy dog._

<em>The quick brown fox jumps over the lazy dog.</em>

Bold and Italic

**_The quick brown fox jumps over the lazy dog._**

<strong><em>The quick brown fox jumps over the lazy dog.</em></strong>

Blockquotes

```
> The quick brown fox jumps over the lazy dog.
> The quick brown fox jumps over the lazy dog.
> 
> The quick brown fox jumps over the lazy dog.
> 
> The quick brown fox jumps over the lazy dog.
> The quick brown fox jumps over the lazy dog.
>> The quick brown fox jumps over the lazy dog.
>>> The quick brown fox jumps over the lazy dog.
> **The quick brown fox** *jumps over the lazy dog.*
```

> The quick brown fox jumps over the lazy dog.

> The quick brown fox jumps over the lazy dog.
> 
> The quick brown fox jumps over the lazy dog.
> 
> The quick brown fox jumps over the lazy dog.

> The quick brown fox jumps over the lazy dog.
>> The quick brown fox jumps over the lazy dog.
>>> The quick brown fox jumps over the lazy dog.

> **The quick brown fox** *jumps over the lazy dog.*

```
Monospaced
<samp>The quick brown fox jumps over the lazy dog.</samp>

Underlined
<ins>The quick brown fox jumps over the lazy dog.</ins>

Strike-through
~~The quick brown fox jumps over the lazy dog.~~
```

Monospaced

<samp>The quick brown fox jumps over the lazy dog.</samp>

Underlined

<ins>The quick brown fox jumps over the lazy dog.</ins>

Strike-through

~~The quick brown fox jumps over the lazy dog.~~

```
Boxed
<table><tr><td>The quick brown fox jumps over the lazy dog.</td></tr></table>
```

Boxed

<table><tr><td>The quick brown fox jumps over the lazy dog.</td></tr></table>

```
Subscript <sub>The quick brown fox jumps over the lazy dog.</sub>
Superscript <sup>The quick brown fox jumps over the lazy dog.</sup>
```

Subscript <sub>The quick brown fox jumps over the lazy dog.</sub>

Superscript <sup>The quick brown fox jumps over the lazy dog.</sup>



# Syntax Highlighting

A class method is an instance method of the class object. When a new class is created, an object of type `Class` is initialized and assigned to a global constant (Mobile in this case).


```
public static String monthNames[] = {"January", "February", "March", "April", "May", "June", "July", "August", "September", "October", "November", "December"};
```


```java
public static String monthNames[] = {"January", "February", "March", "April", "May", "June", "July", "August", "September", "October", "November", "December"};
```

# Alignments
```
<p align="left">
<img src="https://images.unsplash.com/photo-1415604934674-561df9abf539?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=2772&q=80" width="100" height="100" border="10"/>
</p>
```

<p align="left">
<img src="https://images.unsplash.com/photo-1415604934674-561df9abf539?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=2772&q=80" width="100" height="100" border="10"/>
</p>

```
<p align="center">
<img src="https://images.unsplash.com/photo-1415604934674-561df9abf539?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=2772&q=80" width="100" height="100" border="10"/>
</p>
```

<p align="center">
<img src="https://images.unsplash.com/photo-1415604934674-561df9abf539?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=2772&q=80" width="100" height="100" border="10"/>
</p>

```
<p align="right">
<img src="https://images.unsplash.com/photo-1415604934674-561df9abf539?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=2772&q=80" width="100" height="100" border="10"/>
</p>
```

<p align="right">
<img src="https://images.unsplash.com/photo-1415604934674-561df9abf539?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=2772&q=80" width="100" height="100" border="10"/>
</p>

```
<h3 align="center"> My latest Medium posts </h3>
```

<h3 align="center"> My latest  posts </h3>


# Tables

```
<table>
<tr>
<td width="33%"">
The quick brown fox jumps over the lazy dog.
</td>
<td width="33%">
The quick brown fox jumps over the lazy dog.
</td>
<td width="33%">
The quick brown fox jumps over the lazy dog.
</td>
</tr>
</table>
```

<table>
<tr>
<td width="33%"">
The quick brown fox jumps over the lazy dog.
</td>
<td width="33%">
The quick brown fox jumps over the lazy dog.
</td>
<td width="33%">
The quick brown fox jumps over the lazy dog.
</td>
</tr>
</table>



```
| Default | Left align | Center align | Right align |
| - | :- | :-: | -: |
| 9999999999 | 9999999999 | 9999999999 | 9999999999 |
| 999999999 | 999999999 | 999999999 | 999999999 |
| 99999999 | 99999999 | 99999999 | 99999999 |
| 9999999 | 9999999 | 9999999 | 9999999 |


| Default    | Left align | Center align | Right align |
| ---------- | :--------- | :----------: | ----------: |
| 9999999999 | 9999999999 | 9999999999   | 9999999999  |
| 999999999  | 999999999  | 999999999    | 999999999   |
| 99999999   | 99999999   | 99999999     | 99999999    |
| 9999999    | 9999999    | 9999999      | 9999999     |


Default    | Left align | Center align | Right align
---------- | :--------- | :----------: | ----------:
9999999999 | 9999999999 | 9999999999   | 9999999999 
999999999  | 999999999  | 999999999    | 999999999  
99999999   | 99999999   | 99999999     | 99999999   
9999999    | 9999999    | 9999999      | 9999999 
```

| Default | Left align | Center align | Right align |
| - | :- | :-: | -: |
| 9999999999 | 9999999999 | 9999999999 | 9999999999 |
| 999999999 | 999999999 | 999999999 | 999999999 |
| 99999999 | 99999999 | 99999999 | 99999999 |
| 9999999 | 9999999 | 9999999 | 9999999 |


| Default    | Left align | Center align | Right align |
| ---------- | :--------- | :----------: | ----------: |
| 9999999999 | 9999999999 | 9999999999   | 9999999999  |
| 999999999  | 999999999  | 999999999    | 999999999   |
| 99999999   | 99999999   | 99999999     | 99999999    |
| 9999999    | 9999999    | 9999999      | 9999999     |


Default    | Left align | Center align | Right align
---------- | :--------- | :----------: | ----------:
9999999999 | 9999999999 | 9999999999   | 9999999999 
999999999  | 999999999  | 999999999    | 999999999  
99999999   | 99999999   | 99999999     | 99999999   
9999999    | 9999999    | 9999999      | 9999999 


```
<table>
<tr>
<th>Heading 1</th>
<th>Heading 2</th>
</tr>
<tr>

<td>

| A | B | C |
|--|--|--|
| 1 | 2 | 3 |

</td><td>

| A | B | C |
|--|--|--|
| 1 | 2 | 3 |

</td></tr> </table>
```

<table>
<tr>
<th>Heading 1</th>
<th>Heading 2</th>
</tr>
<tr>

<td>

| A | B | C |
|--|--|--|
| 1 | 2 | 3 |

</td><td>

| A | B | C |
|--|--|--|
| 1 | 2 | 3 |

</td></tr> </table>

```
| A | B | C |
|---|---|---|
| 1 | 2 | 3 <br/> 4 <br/> 5 |
```

| A | B | C |
|---|---|---|
| 1 | 2 | 3 <br/> 4 <br/> 5 |

# Links

```
[The-Ultimate-Markdown-Cheat-Sheet]https://github.com/Salman-Ahmad-Khan/Markdown-Cheatsheet/blob/master/README.md)
```

[The-Ultimate-Markdown-Cheat-Sheet]https://github.com/Salman-Ahmad-Khan/Markdown-Cheatsheet/blob/master/README.md)

```
[The-Ultimate-Markdown-Cheat-Sheet][reference text]

[The-Ultimate-Markdown-Cheat-Sheet][1]

[Markdown-Cheat-Sheet]

[reference text]: https://github.com/Salman-Ahmad-Khan/Markdown-Cheatsheet/edit/master/README.md
[1]: https://github.com/Salman-Ahmad-Khan/Markdown-Cheatsheet/edit/master/README.md
[Markdown-Cheat-Sheet]:https://github.com/Salman-Ahmad-Khan/Markdown-Cheatsheet/edit/master/README.md
```

[The-Ultimate-Markdown-Cheat-Sheet][reference text]

[The-Ultimate-Markdown-Cheat-Sheet][1]

[Markdown-Cheat-Sheet]

[reference text]:https://github.com/Salman-Ahmad-Khan/Markdown-Cheatsheet/edit/master/README.md
[1]: https://github.com/Salman-Ahmad-Khan/Markdown-Cheatsheet/edit/master/README.md
[Markdown-Cheat-Sheet]: https://github.com/Salman-Ahmad-Khan/Markdown-Cheatsheet/edit/master/README.md


```
[Example of a relative link](rl.md)
```

[Example of a relative link](rl.md)


Visit https://github.com/

# Images

```
![alt text](https://images.unsplash.com/photo-1415604934674-561df9abf539?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=100&q=80)
```

![alt text](https://images.unsplash.com/photo-1415604934674-561df9abf539?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=100&q=80)

```
![alt text][image]

[image]: https://images.unsplash.com/photo-1415604934674-561df9abf539?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=100&q=80
```
![alt text][image]

[image]: https://images.unsplash.com/photo-1415604934674-561df9abf539?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=100&q=80

```
<img src="https://images.unsplash.com/photo-1415604934674-561df9abf539?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=2772&q=80" width="100" height="100" border="10"/>
```

<img src="https://images.unsplash.com/photo-1415604934674-561df9abf539?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=2772&q=80" width="100" height="100" border="10"/>


<img src="https://media.giphy.com/media/qLHzYjlA2FW8g/giphy.gif" />

<img src="https://img.shields.io/badge/Salman-brightgreen.svg" />

# Lists

```
1. One
2. Two
3. Three
```

1. One
2. Two
3. Three

```
1. First level
    1. Second level
        - Third level
            - Fourth level
2. First level
    1. Second level
3. First level
    1. Second level
```


1. First level
    1. Second level
        - Third level
            - Fourth level
2. First level
    1. Second level
3. First level
    1. Second level
    


```
* 1
* 2
* 3

+ 1
+ 2
+ 3


- 1
- 2
- 3
```

* 1
* 2
* 3

+ 1
+ 2
+ 3


- 1
- 2
- 3


```
- First level
    - Second level
        - Third level
            - Fourth level
- First level
    - Second level
- First level
    - Second level
```

- First level
    - Second level
        - Third level
            - Fourth level
- First level
    - Second level
- First level
    - Second level

```
<ul>
<li>First item</li>
<li>Second item</li>
<li>Third item</li>
<li>Fourth item</li>
</ul>
```

<ul>
<li>First item</li>
<li>Second item</li>
<li>Third item</li>
<li>Fourth item</li>
</ul>

```
- [x] Fix Bug 223
- [ ] Add Feature 33
- [ ] Add unit tests
```

- [x] Fix Bug 223
- [ ] Add Feature 33
- [ ] Add unit tests


# Horizontal Rule

```
---
***
___
```

---

***

___


# Miscellaneous

<!--
Lorem ipsum dolor sit amet
-->

```
*   Asterisk
\   Backslash
`   Backtick
{}  Curly braces
.   Dot
!   Exclamation mark
#   Hash symbol
-   Hyphen symbol
()  Parentheses
+   Plus symbol
[]  Square brackets
_   Underscore`
```

*   Asterisk
\   Backslash
`   Backtick
{}  Curly braces
.   Dot
!   Exclamation mark
#   Hash symbol
-   Hyphen symbol
()  Parentheses
+   Plus symbol
[]  Square brackets
_   Underscore


```
\*   Asterisk
\\   Backslash
\`   Backtick
\{}  Curly braces
\.   Dot
\!   Exclamation mark
\#   Hash symbol
\-   Hyphen symbol
\()  Parentheses
\+   Plus symbol
\[]  Square brackets
\_   Underscore
```

\*   Asterisk
\\   Backslash
\`   Backtick
\{}  Curly braces
\.   Dot
\!   Exclamation mark
\#   Hash symbol
\-   Hyphen symbol
\()  Parentheses
\+   Plus symbol
\[]  Square brackets
\_   Underscore

```
:octocat:
```

:octocat:


```
@salman
```

@salman

```
#
```

\#

