# shortest markdown wow

## 1 for integrated url in text

## 1.1 [this is linux config](https://linuxconfig.org/install-vmware-tools-on-ubuntu-22-04-jammy-jellyfish-linux)

***

__Pragraph Writing__
for writing paragraph "do not do anything, just write and forget" e.g. this is just a sample repo for learning the basics of GitHub.

***
__writing text in many forms__
This is being *created* on a **Friday**  ~~Saturday~~.

<u> And this is my UNDERLINED Text</u>

---
**coding**
This paragraph has some `variable` inline code.

```ios
show configuration 
  dispaly set no more 
```
```javascript
let num = Math.random();
```
___

__Blockquote__
Some paragraph with text.
> blockquote text below the paragraph
  >> Nested Blockquote
---
Ordered List

1. A numbered list
    1. A nested numbered list
    2. Which is numbered
  2. Which is numbered

-OR-

Bullet list

- first time
- second time
- third time
  - indented
    1. inner number

-OR-
* Bullet list
  * Nested bullet
    * Sub-nested bullet etc
* Bullet list item 2

-OR-

- Bullet list
  - Nested bullet
    - Sub-nested bullet etc
- Bullet list item 2


---
Task List
- [ ] An uncompleted task
- [x] A completed task
    
[this is the description](http://www.github.com)

_____

| First Header | Second Header |
| ------------ | ------------- |
| Content Cell | Content Cell  |
| Content Cell | Content Cell  |

*******

`headings can be written as following or refer the top list`
# Learning-Github (heading 1)
## sub heading (heading 2)
### NEW Heading from a Collaborator (heading 3)

this is picture with some random url 
![alt text](http://picsum.photos/200/204)

```
__________

# markdown handy shortcuts
## for headings 
## for bullet points:
- parent bullet point
    -   subsequent bullet point
        -   more indented point
## for different texts:
-   _this text is italic_    
-   **this text is bold**
-   ___this text is also bold+italic___
-   _**this text is also bold+italic**_
-   **_this text is also bold+italic_**
-   > Blockquotes
       >> Nested Blockquotes

## Ordered Lists
1.  First item
2.  Second time or
1.  another first item
1.  another second time but there is no difference is order


## Conventions:
  `let's code defined like this`

## special things to take care 
-   Don't put tabs or spaces in front of your paragraph
-   To create a line break or new line, end a line with two or more spaces, and then type return.


# Configuring GIT
`git config --global user.name "user name"`  
`git config --global user.email "email@email.com"`  
`git config --list`



# GIT + CODE EDITOR SYNC
## GIT Status Messages `kubectl get all`
-    `git status`
### untracked
 -   new file or never committed, git doesn't know abything about it.
### modified
    -   changed at some time but not committed so far
### staged
    -   file is ready to be committed
### unmodified
    -   committed recently e.g. git commit -m "some message"

## GIT Push
    -   ´git push origin main`  # here "origin" is the remote original copy and we can name it anything we prefer to name, and 
                                # "main" is the name of branch 
