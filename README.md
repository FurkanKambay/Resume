# Resume

My résumé written in AsciiDoc using a custom theme. You are welcome to use it as a template or improve it.

> [!IMPORTANT]
> Resume.adoc is not meant to be viewed using GitHub's file preview as it does not render properly. It is used as a source file for PDF exports via `asciidoctor-pdf`. It can also be previewed using the `AsciiDoc` VS Code extension.

## How to export as PDF

- Install Ruby
  - Using scoop: `scoop install ruby`
- Install [`asciidoctor-pdf`](https://github.com/asciidoctor/asciidoctor-pdf):
  - `gem install asciidoctor-pdf`
- Run the provided VS Code task to create PDF
  - Alternatively, run `asciidoctor-pdf Resume.adoc` from a terminal.
