#Standard Markdown
##Headers
#H1
###H3

##Italic & Bold
*Italic*
_Italic_

**Bold**
__Bold__

___Bold & Italic___
***Italic & Bold***
__*Bold & Italic*__     not work
**_Italic & Bold_**     not work

##Lists
###Unordered
* Item1
* Item2
  * Item2-1
  * Item2-2
* Item3

###Ordred
1. Item1
2. Item2
  1. Item2-1
  2. Item2-2
3. Item3
  * Item3-1
  * Item3-2

##Images
![Imgae](http://www.baidu.com)

##Links
[Links](http://www.baidu.com)

##Blockquots
As someone said:
>Something
>Something else

##Inline code
`var a = 1`

#GitHub flavored markdown
##Syntax highlighting
1. Specify the language
```java
String title = "Markdown"
System.out.println(title);
```

2. Simple indent by 4 spaces
    String title = "Markdown"
    System.out.println(title);

##Task Lists
- [x]   @mention, #ref, [link](), **formatting** and <del>tags</del> support
- [x]   list syntax required
- [x]   this is a complete item
- [ ]   this is an incomplete item

##Tables
First Header|Second Header
Content from cell1|Content from cell2
Content in the first column|Content in the second column   