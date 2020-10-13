# Markdown Cheatsheet
## Here is a Second Header
### Here is a Third Header
#### You get the idea

You can use *asterisks* or _underscores_ for emphasis (*italics*).  
You can use **double asterisks** or __double underscores__ for strong emphasis (**bold**).  
You can combine emphasis using **asterisks and _underscores_**.  
Using two tildes provides a strikethrough or so I was told by ~~a totally real doctor~~.  

# Lists

1. First item in ordered list
2. Next item in ordered list
    * Unordered item in sub-list
1. Actual numbers don't matter, just that it's a number
    1. Ordered sub-list
2. And another item

   You can have properly indented paragraphs within list items. Notice the blank line above, and the leading spaces (at least one, but we'll use three here to also align the raw Markdown).

   To have a line break without a paragraph you will need to use two trailing spaces.  
   Note that this line is separate, but within the same paragraph.  
   (This is contrary to the typical GRM line break behaviour, where trailing spaces are not required.)

* Unordered lists can use asterisks
+ Or pluses
- or minuses

# Links  

**Inline Style Link:**  
[Google](https://www.google.com)  

**Inline-style With Title:**
[Google](https://www.google.com "Google's Homepage")  

**Reference Style Link:**
[Reference Style Link][Arbitrary case-insensitive reference text]
.
.Later down the page
.
[Arbitrary case-insensitive reference text]: https://www.mozilla.org

**Reference Style Link Using Numbers**
[Reference Style Link Using Numbers][1]
.
.Later Down the Page
.
[1]: http://slashdot.org

# Images

`Inline-style:
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")  

Reference-style:
![alt text][logo]

[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 2"`