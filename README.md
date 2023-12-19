# demo
Headers
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

Font
*Italics*
_This will also be italic_
**Bold text**
__This will also be bold__
***Bold and Italics***
_You **can** combine them_
~~Striked Text~~
***~~Italic, bold, and strikethrough1~~***	

Lists
Unordered

* Item 1
* Item 2
  * Item 1a
  * Item 2a
     * Item 1b
     * Item 2b

Lists
Ordered

1. First
2. jhg
   1. Second
   2. jhg
      1. Third
      2. jhg

Links
* [Link with more info with various formatting options](https://docs.github.com/en/githubwriting-on-github "more info")
* https://www.google.com/
* <https://www.google.com/>


Link Label
[My GitHub][GitHubLink]

Links to the URLs in a repository
[Example document](/example/example.md)

Example document

[example](./example)


Inserting Images or Gifs using links
![alt](URL "title")
![Octocat](https://user-images.githubusercontent.com/81953271/124010886-b571ca80-d9df-11eb-86ac-b358c48ac6aa.png "Github logo") 
<img src="https://github.com/darsaveli/Mariam/blob/main/1479814528_webarebears.gif" width="385px" align="center">

Other options to resize:

![](https://  link | width=100)

[![Octocat](https://user-images.githubusercontent.com/81953271/124010886-b571ca80-d9df-11eb-86ac-b358c48ac6aa.png "GitHub Logo")](https://github.com/)

Tables
|Header1|Header2|Header3|
| --- | --- | --- |
| This | is a | table |
| This | is 2nd | row |
| This | is 3rd | row |

Align
You may specify alignment like this:

| Align left | Centered  | Align right |
| :------------ |:---------------:| -----:|
| col 3 is      | some wordy text | $1600 |


CheckBox
* [ ] Checkbox1

* [ ] Checkbox2

* [x] Checkbox selected

* [ ] Quoting Text
> This is a block quoted text

Multi-level blockquotes
> Asia
>> China
>>> Beijing
>>>> Haidian
>>>>> Tsinghua
>>>>
>>>>Text highlighting
`linux` `ubuntu`
>>>
>>>Horizontal Line
***
___
--- 
All three will be rendered as:

p.s.

<hr> works too


Break between lines
<br>
Visible markdown characters
```git
 * __ <br> etc ```
Multi-line text
aaa,
sss,
ddd!


Add 1 tab or 4 spaces at the beginning of several lines of text.

OR

Use three backticks:

asd,
sfd,
wer!
This syntax can also be used for code highlighting


Comments in Markdown
<!-- comment written in markdown -->
They will be invisible on readme


Emoji
:grinning:	or just place the emoji 😀


Code Block
There are three ways to add code in markdown

Inline Code (single backtick)
Whitespace
    `this` is an example of inline code.
four spaces work too!
Fenced code blocks With GFM you can wrap your code with three back quotes to create a code block without the leading spaces. Add annoptional language identifier and your code will get syntax highlighting.
public static void main(String[]args){} //Java
document.getElementById("myH1").innerHTML="Welcome to my Homepage"; //javascipt


Syntax Highlighting
If language name is mentioned after the end of first set of backticks, the code snippet will be highlighted according to the language.

```js
console.log('javascript')
```

```python
print('python')
```

```java
System.out.println('java')
```
   
```json
{
  "firstName": "A",
  "lastName": "B
  "age": 18
}
```
console.log('javascript')
print('python')
System.out.println('java')
{
  "firstName": "A",
  "lastName": "B",
  "age": 18
}


diff syntax
In the version control system, the function of diff is indispensable, i.e., the addition and deletion of a file content is displayed. The diff effect that can be displayed in GFM. Green is for new, while red is for deleted.

Syntax
The syntax is similar to code fenced code blocks, except that the diff is written after the three backticks. And in the content, the beginning of +  indicates the addition, and the beginning of -  indicates the deletion.

+ Hello world!
- This is useless.

Use YAML: human friendly data serialization language for all programming languages
name: Mariam
located_in: ***
from: ***
education: ***
job: ***
company: ***


Anchor
In fact, each title is an anchor, similar to the HTML anchor (#), e.g.

Syntax	Look like
[Back to top](#readme)	Back to top
Note that all the letters in the title are converted to lowercase letters.


Render mathematical expressions in Markdown
You can now use LaTeX style syntax to render math expressions within Markdown inline (using $ delimiters) or in blocks (using $$ delimiters).

Writing expressions as blocks To add math as a multiline block displayed separately from surrounding text, start a new line and delimit the expression with two dollar symbols $$.


$$\left( \sum_{k=1}^n a_k b_k \right)^2 \leq \left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)$$
Writing inline expressions
To include a math expression inline with your text, delimit the expression with a dollar symbol $.

This sentence uses $ delimiters to show math inline: 

This sentence uses `$` delimiters to show math inline:  $\sqrt{3x-1}+(1+x)^2$


