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
