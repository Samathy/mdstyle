### mdstyle

Takes HTML output (from markdown) through stdin and adds some basic styling
to it ready to pipe it into an html to pdf generator.

LICENSE:
MIT

#### Usage:

    markdown document.md | mdstyle | wkhtmltopdf - out.pdf


