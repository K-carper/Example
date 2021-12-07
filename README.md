# Markdown Syntax Notes
Headings
--------
### Those are the 2 ways to create headings

The blank line above is used to sperate lines of text and therefore create a paragraph.

Don't use tabs in front of written paragraphs, always keep the lines left-aligned.
Adding 2+ spaces at the end of a line,   
creates a line break like this.
Similar to HTML, <(br)> <br>
also works.  

## Emphasis can be added with bold or italic text
To make a word or phrase **bold**, you can use 2 **astericks** or __underscores__ before and after the word/phrase
But when making letters in the middle of a word only use asterciks, ex: Love**is**bold

To make a word or phrase *italicized*, you can use 1 *astericks* or _underscores_ before and after the word/phrase
But when making letters in the middle of a word only use asterciks, ex: Love*is*bold

To make a word/phrase ***bold and italicized*** you can use 3 ***astericks*** or ___underscores___ before and after the phrase/word.
But when making letters in the middle of a word only use asterciks, ex: Love***is***bold

To use block quotes you add a (>) in front of the paragraphs
> This is a regular block quote:
>
> It can be used for entire paragraphs by inserting the symbol on the blank line between
>> 2 (>) symbols would render a nested blockquote like this.
## Ordered Lists can be created by adding numbers and periods
1. First item
2. Second item
3. Third item
4. Fourth item

They can be indented according to the lines number placement: 
1. First item
2. Second item
3. Third item
    1. Indented item
    2. Indented item
4. Fourth item
## Unordered Lists can be created using (-), (*), or (+) 
+ First item
+ Second item
+ Third item
    + Indented item
    + Indented item
+ Fourth item
If you need to start an unordered list item with a number followed by a period, you can use a backslash (\) to escape the period.
- 1968\. A great year!
- I think 1969 was second best.	

### Code Blocks
Code blocks are normally indented four spaces or one tab. When they’re in a list, indent them eight spaces or two tabs.
1. Open the file.
2. Find the following code block on line 21:

        <html>
          <head>
            <title>Test</title>
          </head>

3. Update the title to match the name of your website.

### Images 
1. Open the file containing the Linux mascot.
2. Marvel at its beauty.

    ![Tux, the Linux mascot](/assets/images/tux.png)

3. Close the file.

## Code
To denote a word or phrase as code, enclose it in backticks (`).
At the command prompt, type `nano`.
### Escaping Backticks
``Use `code` in your Markdown file.``

## Horizontal Rule 
Try to put a blank line before...

---

...and after a horizontal rule.

## Links can be created by eclosing the Link Text in brackets
My favorite search engine is [Duck Duck Go](https://duckduckgo.com).

Markdown applications don’t agree on how to handle spaces in the middle of a URL. For compatibility, try to URL encode any spaces with %20.  
[link](https://www.example.com/my%20great%20page)	

## Images
To add an image, add an exclamation mark (!), followed by alt text in brackets, and the path or URL to the image asset in parentheses.  

![The San Juan Mountains are beautiful!](/assets/images/san-juan-mountains.jpg "San Juan Mountains")

## Escaping Characters: \', \*, \_, \{}, \[], \<>, \(), \#, \+, \-, \., \!, \|
To display a literal character that would otherwise be used to format text in a Markdown document, add a backslash (\) in front of the character.

\* Without the backslash, this would be a bullet in an unordered list.

## Video Hyperlink
You need a pair of brackets \[\] for the link's text that's shown on the page, and a pair of parentheses \(\) for the hyperlink's URL:
[Inserting Links](https://youtu.be/0aJCGOxeHVk)
