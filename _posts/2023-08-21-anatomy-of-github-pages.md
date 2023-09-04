---
layout: default
title: Anatomy of Github Pages
type: hacks
courses: { compsci: {week: 1}}
---
### Anatomy of GitHub Pages Hacks

Files and Directories in this Project
Here are some  things I did to key directories/projects

- README.md: This file contains instructions and background information about the project. It is a standard file present in all properly set up GitHub projects.

- index.md: This is the source file for the home page of the project. It is a standard file for all GitHub Pages projects. Note that Markdown (.md) files are converted to HTML by the Jekyll build process. HTML files are the only file type that is rendered on a website. I changed my home page and added images, gifs, and videos to my site directly on markdown so that it would generate a html file based on markdown.

_notebooks: This directory contains Jupyter Notebook (.ipynb) files. These files are converted to Markdown (.md) files by the Makefile rules in the build process. The Markdown files are then converted to HTML by the Jekyll build process. I was able to make my first  working python file and put in one of my blog pages (Check out python io)

_posts: This directory contains Markdown (.md) files that will be part of the website. These files are formatted similarly to index.md and include frontmatter (metadata coded in YAML) and Markdown, HTML, JavaScript, and CSS source code. You will also find Liquid code in these files, which is used to generate Markdown, HTML, JavaScript, and CSS. I updated several markdown pages-I created tools.md to blog about tools I use and enjoy!!!

_data: This directory is the standard location for storing data files that support the _posts or _notebooks directories.

images: This directory is the standard location for storing image files (JPEG, PNG, etc.) that support the _posts or _notebooks directories.

_config.yml: This file contains YAML definitions (key-value properties) used to build the Jekyll website.

.gitignore: This file specifies elements to be excluded from version control. Files are excluded when they are derived from the original source and not considered part of the project’s source code. In the VSCode Explorer, you may notice some files appearing dimmed, indicating that they are purposely excluded by the rules in .gitignore.




Changing the Theme
Google “github pages themes” or this theme link. The purpose of this section is to help you change your Theme options.

_config.yml contains commented out alternatives to themes (see ‘# theme requirements’ cell below). Try these themes by commenting out midnight them with # at front and remove comment # from the front of theme of choice. After changing theme you will need to do a make clean followed by a make to test