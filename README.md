This is a collections of notes of useful codes and tips that I will use to build my github, I will try to add to this everytime I learnt something new, it will start as a list and when I start to learn lots of things I will try to create a table of lists and add in codes to make this more presentable. 

I am well aware that these codes are not the standardise way or the best way to write a markdown file, it is my personal preference and they will surely change over time, so if anyone found a better way you are surely wellcome to enlight me. I am writing this file as a learning process. 

-----------------------------------------------------------------------------------------------

# Markdown files

### 1.0 Markdown Basics https://help.github.com/articles/basic-writing-and-formatting-syntax/ 

### 1.1 Headings 
I found #heading ##heading and ###heading most useful, I tried to add color and change font but I dont think I can, and later realised that I don;'t actually need to, just keep things simple and concise and future me will surely thank my decision. 
```markdown
> # heading
> ## heading
> ### heading
> #### heading
> ##### heading
> ###### heading
```
# heading
## heading
### heading
#### heading
##### heading
###### heading

---------------------------------------------------------------------------------------------

### 1.1 Paragraphs
Paragraphs are separated by empty lines. To create a new paragraph, press <return> twice.

```markdown
> Paragraph 1
>
> Paragraph 2
```
Paragraph 1

Paragraph 2

MD file will automatically attach your paragraphs if there is no empty line separating your paragraphs, I often accidently make this careless mistake and had to edit my codes. 
```markdown
> Paragraph 1
> Paragraph 2
```
Paragraph 1
Paragraph 2

--------------------------------------------------------------------------------------------------------

1.2 Quotes
```Markdown
> ### Blockquoted header
> This is blockquoted text.
> This is a second paragraph within the blockquoted text.
```
> ### Blockquoted header
> This is blockquoted text.
> This is a second paragraph within the blockquoted text.

```Markdown
> ### Blockquoted header
>
> This is blockquoted text.
>
> This is a second paragraph within the blockquoted text.
>
> hello\
>
> world
>
```
> ### Blockquoted header
> This is blockquoted text.
> This is a second paragraph within the blockquoted text.
> hello\
>
> world

----------------------------------------------------------------------------------------------------------

----------------------------------------------------------------------------------------------------------
### 2. Add emoji to repository description :smiley: 
  - Emoji by type https://www.webpagefx.com/tools/emoji-cheat-sheet/
  - Emoji by alphabet https://readme.io/emojis/
  - Japanese Emoticons ╮(╯∀╰)╭ https://www.jemoticons.com/en/kiss/
------------------------------------------------------------------------------------------------------------
3. Create tables
https://help.github.com/enterprise/11.10.340/user/articles/github-flavored-markdown/

| Left-Aligned  | Center Aligned  | Right Aligned |
| :------------ |:---------------:| -----:|
| col 3 is      | some wordy text | $1600 |
| col 2 is      | centered        |   $12 |
| zebra stripes | are neat        |    $1 |

List of supported languages and lexers (by [Jeanine Adkisson](https://github.com/jneen/rouge/wiki/List-of-supported-languages-and-lexers)

```markdown
if (isAwesome){
  return true
}
``` 

<mark>Marked text</mark>
---
# R
1. set up git on R 
2. Connect guithub with R [paste Blasee's repository here]
---

# Notes
Maybe expand this to a Today I learnt? with Git R SAS SQL SPSS HTML PYTHON etc
like this one https://github.com/jbranchaud/til
