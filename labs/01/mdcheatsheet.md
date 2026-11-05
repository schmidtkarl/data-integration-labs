# Markdown cheat sheet by Karl

> #### Markdown is a simple programming language. <br> It's main purpose is to style text without complicated code labels.
____________________________________


# The 'whats' and 'hows'
Click a topic for easy navigation. 
| Topic |
|------|
|Text|
|Lists|
|Links & Images|
|Code|
|Quotes|
|Tables|
|Layout|
|Github Extras| 

## Text
The _essence_ of Markdown

### Headings


```markdown
# title
gives you:
```
# This is a title
```markdown
## this is a sub title
gives you:
```
## This is a sub title

Continue with corresponding # till you reach 6 - that's the max \ 
see: ####### bonjour

### This is a heading

#### This is a subheading

##### This is a sub-subheading



### Paragraphs and line breaks
Markdown can behave in peculiar ways when formatting text, especially in github. 

When writing and writing and writing markdown let's you continue a line of text indefinitly. To break it on to a new line use \ at the end or ``` <br> ``` in between. To spaces at the end of a sentence followed by an enter also does the job.

### Formatting text
Usefull for emphasizing certain words or pieces of text. 

```markdown
get bold text by using ** around your text = **ABSOLUT VODKA**
```
**ABSOLUT VODKA**

```markdown
To get you text italic use either a single asterix * or lower line _

e.g. _hello my name is Bob_
    *hello my name is bob*
```
_hello my name is Bob_ <br>
*hello my name is bob*

```markdown
if you want to achieve both bold and italic styling on a work or sentence, do this:
**_you rock_**
```
**_you rock_**

```markdown
striking thorugh text can be achieved by using two tildes ~~ 
~~this text is struck through~~

```
~~this text is gone~~ 


```markdown
if you want to escape a character, you need to precede them with a backslash.
that would look like this \*this text is not bold\*
```
check: \*this text is not bold\*
\\
\ 

barking barking \
barking barking \\


````markdown
writing code in markdown can be achieved my using minimum of three backticks ` <br> followed by the programming language, although this is optional.
```vibe
this is vibecode man
```
wenn nesting, you need to increase the hirarchy by increasing the number of backticks. = always more than three. 
````



### Lists

```markdown
unordered
* item 1
* item 2
* item 3
```
* item 1
* item 2
* item 3

```markdown
ordered
1. item 1
2. item 2
3. item 3
```
1. item 1
2. item 2
3. item 3

```markdown
nested
* mega item 1
  * subitem 1
```
* mega item 1
  * subitem 1

```markdown
tasklists
- [x] To do 1
- [ ] To do 2
- [ ] To do 3
```
- [x] To do 1
- [ ] To do 2
- [ ] To do 3

### Links and images

Images rarely find their way into Mardkown, but when they do, this is how to style them: 
 for the best styling guide for images in Github I can best refer to [apaskulin on github Gist](https://gist.github.com/apaskulin/1ad686e42c7165cb9c22f9fe1e389558)
<br>
For working with images in plain native Markdown do the following
```markdown
put your image in a location easily accessible for the environment you are running
say local folder or your github repo.
![my old dog](/assets/images/picture_dog.png)
```

_Copied from Markdownmastery.com_ <-- here you can also find out how to give any image an alt text. 
```markdown
To make an image clickable, wrap it in a normal Markdown link: [![Diagram](images/arch.png)](https://example.com). <br>
That creates a linked image. A regular Markdown link and a Markdown image are different: a link sends the reader to <br>
another page, while an image displays visual content. If you need both behaviors, combine them as shown above.
```


_Copied from the Obsidian Markdown Cheat Sheet_
```markdown
To create a link to a webpage:
[text for the link](https://example.com/)
To link to a page in your vault (create a local link):
[[Resources/some page]]
To link to a header in your vault (another local link):
[[Resources/some page#Header]]
To change the text for a local link: use the | character:
[[Resources/some page|this will show up instead]]
```

### How to link to other sections and other pages
Given you hae a larch markdown file; you may benefit from <br>
linking to certain locations or chapters in your text.
[Going through the motions](#links-and-images) <br>

 this is what you would write:
 
 ```markdown
[Going through the motions](#liks-and-images)
```

**now, for linking to other github repos** <br>
you take the link and then just put it in brackets after your square brackets. 

### _in github however..._
you can also give a relative path name and the markdown will take it. <br>
for example: 
```markdown
[this links to my other githubrepo](relative path/goal.extension) <br>
done
```
> for linking to another file in the same folder, the relative path is sufficient.
> the absolut path will work too.

_**when linking to another repo**_ you must use the absolute path = link = url 

### code in markdown
Can be displayed by writing a minimum of three backticks followed by the name of the code language: 
```python
print("hello world"
```
```bash
this is bash
```
INLINE CODE CAN ALSO BE shown with single backticks


```json
this is json
```

### using block quotes and quotes 

What are block quotes? And what are quotes? 




