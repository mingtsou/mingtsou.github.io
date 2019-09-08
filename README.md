This site is published at https://mingtsou.github.io/

Here is the Basic writing and formatting snytax for Markdown on Github.
https://help.github.com/en/articles/basic-writing-and-formatting-syntax#quoting-code

## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/mingtsou/mingtsou.github.io/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/mingtsou/mingtsou.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

### How to Create a New Folder, called "Images"?

Since Git index can only list "files", rather than "folders", you can not create an empty folder inside a Repo. You MUST create some files with a new folder first.  Here is the steps to create a new folder with a README markdown.

1. go to the folder inside which you want to create another folder.
2. click on New file.
3. on the text field for the file name, first write the folder name you want to create, then type /README.md
4. you can add more folders similarly.


### How to add a images in your Github.io webpage?

1. If the images is from an external webpage, just use the format 

```markdown
![Image_text](src)
![HDMA LOGO](https://humandynamics.sdsu.edu/images/HDMA_Logo.png)

```

![HDMA LOGO](https://humandynamics.sdsu.edu/images/HDMA_Logo.png)

### How to delete a folder in Github?

You can delete a file using delete button but you cannot directly delete a folder via the web-interface. The way to delete a folder from GitHub.com is to delete every file inside it. Once you delete all files inside a folder.  The folder will no longer exist.

### Website default file is README.md or index.html?

The Github website (io) will check if there is a "index.html" file available.  If this file is available, Github will use the "index.html" as the default web page in this folder.  Otherwise, the README.md will be the default webpage. 
 
