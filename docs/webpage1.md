---
title: Introduction to Markdown
layout: default
nav_order: 1
---
  
  For Lesson 2 of the tutorial.
  
  ![Coding Picture](https://thumbor.forbes.com/thumbor/640x640/https://blogs-images.forbes.com/forbestechcouncil/files/2019/01/canva-photo-editor-8-7.jpg?width=960)
  
  # List of Useful Markdown Features
  * Headings of a number of different levels (6 sizes)
  ```
  # First-tier heading
  ## Second-tier heading
  ### Third-tier heading
  ```
  * bolded, italicized text
  ```
  *italic text*
  _italic text_
  
  **bold text**
  __bold text__
  
  _Italic **and bold** text_
  ```
  * insert an image from the *web* (**note**: if the image is later moved from the url, the file will break)
  ```
  ![Alt Text](url)
  ```
  * insert an image that is hosted in your *GitHub repository* (basically same syntax as web, but url will be from Github)
  ```
 ![Alt Text](/images/logo.png)
  ```
  * An ordered list
  ```
1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b
  ```
  * A bulleted list
  ```
  * Item 1
  * Item 2
    * Item 2a
    * Item 2b
  ```
  * A link to another website
  ```
http://github.com - automatic!
[GitHub](http://github.com)
  ```
  * A snippet of code
  ```
  Inline: within `code` a sentence
  Block: fence the code with ``` before and after (other ways too)
  ```
  * A table (- = row, | = column)
  ```
  First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column
  ```
  * And finally, an emoji!
  ```
  :EMOJICODE:
  ```

## Resources
1. [Mastering Markdown](https://guides.github.com/features/mastering-markdown/)
2. [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
3. [Markdown Introduction](https://daringfireball.net/projects/markdown/)
4. [Emoji Code List](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md) 😄
