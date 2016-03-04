# Content source files for Hevnly Holy Grail

![Travis build status](https://travis-ci.org/hevnly/hhg.svg?branch=develop)

## How to Deploy

1. Install bloginator using npm
2. Run `bloginate` in the root directory
3. Serve the build directory using a static http server

## How to post
1. You can read about markdown syntax in [markdown cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet), but generally you will need these:
- *\*italics\**
- **\*\*bold\*\***
- \[link name](http://link.com)
- \!\[image alt text](image-file-name.jpg)
- \>Quote text
- \- bullet list item
- 1\. numbered list item

2. Write your article using a markdown editor or even a simple note editor (except ms notepad).
A useful one is [stackedit](https://stackedit.io/editor).

3. Images should be named with **lowercase latin characters**, **numbers** and **dashes**. They should **not** contain capitals, spaces or any special character like
    ```
    !¡@#™€¢∞§¶•ªº–≠$£%^&*()[]{}<>_+=.,:;'"?/|\\`~
    ```
    Images should be placed in:
    ```
    /source/images/**EDITION_NUMBER**/**POST-SLUG**/ .
    ```
    For example if my post is named Foo Bar and belongs to the 5th edition, it should go in:
    ```
    /source/images/5/foo-bar/
    ```

4. At the top of your markdown file add some useful metadata:
    ```
    ---
    title: "How to post in hevnly magazine"
    subTitle: "Also known as HHG"
    readingTime: 4min
    heroImage: hhg-post-hero.jpg
    date: 2015-11-20
    slug: hhg-post
    tags: markdown, blog, magazine, metadata
    category: product
    editionName: posting
    editionNumber: 1
    ---
    ```

5.  Save your markdown file using the following naming convention:
    ```
    POST_DATE + POST_SLUG + .md
    ```
    eg
    ```
    2015-10-21-back-to-the-future.md
    ```

1234567
