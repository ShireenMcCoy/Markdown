# Shireen's Guide to Markdown `` (: ``

# Heading 1 - starts with a hashtag/pound sign/octothorp `#`
(Alternately, you can add any number of equals signs `===` on the line below the heading 1 line.)
## Heading 2 - starts with two `##`
(Alternately, you can add any number of dashes `---` on the line below the heading 2 line.)
### Heading 3 - starts with three `###`
#### Heading 4 - starts with four `####`
##### Heading 5 - starts with five `#####`
###### Heading 6 - starts with six `######`
(There is no heading 7 or greater)

Two underscores `__` or two stars `**` on both sides of a word makes it __bold__<br>
One star `*` or one underscore `_` on both sides of a word *italicizes* it<br>

Monospace text is surrounded by `` `backticks.` ``

Three stars `***` makes a horizontal line:
***
- Unordered list items start with a hyphen `-` or asterisk `*` with a space before the text. 
    - Sub bullet points have a tab before the hyphen `-` or asterisk `*`

1. Ordered list items start with number, a dot, and a space.
11. The first item will be whatever number you type.
5. Each number you add after that will be renamed so that they follow sequentially from the first number.
6. For example, if you make a list and number your entries 5, 7, 3, 14, they will display as 5, 6, 7, 8. 
    1. Adding a tab, followed by a number and a dot, will give you a sub-item.
 
   
![my image](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQcPlrrfup8Z2kVr9o4aLnWf47CkbuLB29-tA&usqp=CAU)
    
To add **images** in Markdown, type `![image_name](path_to_image)`, where `image_name` is a name you give the image, and `path_to_image` is the url or filepath to the image.

To add a [link](https://www.markdownguide.org/basic-syntax/), use `[link text](url)`, where `link text` is what you want people to click on, and `url` is where you want them to go. 

>This is a blockquote. Blockquotes start with a "greater than" symbol `>`.   
>> Blockquotes can be nested. Just put `>>` in front of  the first nested blockquote ...
>>> ... and `>>>` for the next nested blockquote
>>>> until you have as many as you like!

If you want to display a ~~crossed-out~~ word in markdown, surround it with two tildes `~~` (no space before the word) on each side.

To add a table, put a pipe `|` between each column name and column item. Put three or more hyphens `---` below the line that contains your column names. It's not always required, but you can also add pipes `|` on at the beginning and end of each row. This makes it look clean and readable even in plain text format:

`| Name Col 1   | Name Col 2   |`\
`| -----------  | -------------|`\
`| item 1 col 1 | item 1 col 2 |`\
`| item 2 col 1 | item 2 col 2 |`
 

**renders as:** 

| Name Col 1   | Name Col 2   |
| -----------  | -------------|
| item 1 col 1 | item 1 col 2 |
| item 2 col 1 | item 2 col 2 |


### The End!
