# Continue Development and Continue Presentation Framework

The purpose of this framework is to introduce CI/CD methods to contents development and presentation.

The framework use [reveal.js](https://github.com/hakimel/reveal.js "reveal.js") to do the presentation.
All the contents should write in Markdown format. Put the **md file** into folder *markdown*, put all the pictures to folder *image*.

## How to run the presentation
There are 2 methods.
1.	Clone the framework to local and host the code on any local web server. Click index.html to start the presentation
2.	Clone the framework to your GitHub repository, run the code directly via https://<yourgit_id>.github.io/reveal.js/

## How to change to your markdown file
* Copy your **markdown file** to the folder markdown
* Locate **index.html**. Replace your_markdown.md to your markdown file name.

```html
<section data-markdown="markdown/<your_markdown.md>"
  data-separator="^\n\n\n"
  data-separator-vertical="^\n\n">
</section>
```
