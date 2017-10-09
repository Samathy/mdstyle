### mdstyle

Takes HTML output (from markdown) through stdin and adds some basic styling
to it ready to pipe it into an html to pdf generator.

LICENSE:
MIT

#### Usage:

    markdown document.md | mdstyle | wkhtmltopdf - out.pdf

#### ToDo:

 [] Add command line args to specify: margin, sizes, center etc
 [] Add command line args to point to style sheet
 [] Write Markdown parser & integrate
