Many things that we use, to make readme file well, first of All   
# 1.heading:  
To make heading we use # sumbol with one space and write the text that we want to include in your heading.
# Heading level 1  
## Heading level 2  
### Heading level 3  
#### Heading level 4  
##### Heading level 5  
###### Heading level 6  
# 2.Paragraphs:
to make pragrahs we write text of paragraph as etis
# 3.Italic:
Wrap the item with One star/underscore on each side. for example    
*one star on each side*  
_This text is also italic_   
# 4.Line breaks
To insert a line break into your Markdown file, finish your line with at least two spaces and press Enter. It will render a new line for your text.
# 5.Bold
Wrap the item with Two stars/underscores on each side. for example  
**two stars on each side**  
__This text is also bold__    
# 6.Simultaneously Bold and Italic:
Make your text Simultaneously bold and italic to give it even more weight!  
Use three asterisks (or three underscores) to wrap your word or phrase.  
***This text is italic and bold.***  
___This text is also italic and bold.___  
# 7.Striking through: 
Wrap the item in two tildes ~~ on each side.  
~~strikethrough~~  
# 8.Links:
To link to external websites in Markdown content use two sets of brackets.  
Wrap link text in brackets [ ], and then wrap the URL in parentheses ( ): [ ]( ).  
[This text links to gfg](https://write.geeksforgeeks.org/).   
# 9. Images:
Inserting an image into your Markdown file is similar to the formatting for links.  
Begin your image formatting with an exclamation mark. Next, use square brackets to wrap your image alt text, next to parentheses containing the URL for your image.  
Ensure there are no spaces between the exclamation mark, square brackets, or parentheses.  
![image](https://media.geeksforgeeks.org/wp-content/cdn-uploads/20210914130327/100-Days-of-Code-with-GFG-Get-Committed-to-a-Challenge.png)  
# 10. Unordered lists:
Markdown allows you to format your lists with several different symbols: asterisks (*), hyphens (-), or plus signs (+).  
It’s up to you to choose which symbol you prefer. The result you get is the same.  
-Just add a dash first and then write a text.  

-If you add another dash in the following line, you will have another item in the list.  
    - If you add four spaces or use a tab key, you will create an indented list.  
        - If you need sert an indenta list within an intended one, just press a tab key again.  

Sometimes you want bullet points:  

*Start a line with a star   
*Profit!  
# 11. Ordered lists:  
Format your ordered lists by preceding each list item with a number, followed by a full stop and then a space.  
In Markdown, it doesn’t matter which numbers you use to format your list, as the list will always render as 1, 2, 3, and so on.  
1. Just type a number follow by a dot.  
2. If you want to add a second item, just type in another number followed by a dot.  
1. If you make a mistake when typing numbers, fear not, Markdown will correct for you.   
    1. If you press a tab key or type four spaces, you will get an indented list and the numbering will start from scratch.  
        1. If you want to insert an indented numbered list within an existing indented numbered one, just press the tab key again.   
            -If need be, you can also add an indented unordered list within an indented numbered one, by pressing a tab key and typing adash.
# 12. Blockquotes:  
Sometimes in Markdown, we will want to reference an external source using quotation marks. It is called a blockquote.   
You represent any blockquote by preceding the first line of the block quote with a greater-than sign or angle bracket (>).  
> This is a blockquote  
> This is a blockquote  
> This is a blockquote    
 # 13.Horizontal rules:
A horizontal rule is a tiny functional element that you can use to visually split up blocks of text within your Markdown file.  
We represent a horizontal rule by three or more hyphens (-), asterisks (*), or underscores (_).  
---  
* * *    
___  
# 14. Code snippets:
To reference snippets of code as examples, format code snippets using backticks ` that wrap your code snippet.   
The first backtick “opens” the snippet, and the second backtick “closes” it.  

`This is a code snippet.`  
# 15. Code blocks:
Formatting code blocks is useful when you have a bigger chunk of code to include in your Markdown file.  
Format your code blocks by indenting every line of your code block using one tab or four spaces.  
And if you’d like to use syntax highlighting, including the language.  
Example:

```javascript

if (isAwesome){

 return true

}

```
# 16. Escaping:
In Markdown, you will often need to include characters in your text (for example, an asterisk) that may be part of the Markdown syntax.   
You need to “escape” these characters, so your Markdown application doesn’t read these characters as formatting.     
You escape characters in Markdown using a backslash before the character, with no space in between.   
Syntax:

\ backslash  
` backtick  
* asterisk   
_ underscore  
{} curly braces  
[] square brackets  
() parentheses  
#hash symbol  
+ plus sign  
– minus sign (hyphen)  
. dot  
! exclamation mark  
# 17. Lists within a blockquote:  
Nest your list formatting inside your blockquote formatting.    
Format your blockquote using a greater-than sign (>) followed by a space, including a sign before every line of your blockquote.  
Add your list formatting (*) just after your greater-than signs.  
Example:

> This is a blockquote
> * This is a list item within a blockquote    
> * This is a list item within a blockquote    
> * This is a list item within a blockquote
> * # 18. Quotes:  
Add a quotation with the > character at the beginning of each line.  
Example:

> "I make Jessica Simpson look like a rock scientist." 

> —Tara Reid, actress
> # Task Lists:  
To create a task list  
If you include a task list in the first comment of an Issue, you will get a handy progress indicator in your issue list.  
It also works in Pull Requests.  
Example:

- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported   
- [x] list syntax required (any unordered or ordered list supported)   
- [x] this is a complete item   
- [ ] this is an incomplete item

- [ ]    
# Tables:
You can create tables by assembling a list of words and dividing them with hyphens – (for the first row), and then separating each column with a pipe (|).
Example:

First Header | Second Header 
 ------------ | ------------- 
Content from cell 1 | Content from cell 2 
Content in the first column | content in the second column
