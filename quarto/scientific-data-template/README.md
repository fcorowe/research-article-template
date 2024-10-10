# Scientific-data Format

## Creating a New Article

To create a new article using this format:

```bash
quarto use template christopherkenny/scientific-data
```

This will create a new directory with an example document that uses this format.

## Using with an Existing Document

To add this format to an existing document:

```bash
quarto add christopherkenny/scientific-data
```

Then, add the format to your document options:

```yaml
format:
  scientific-data-pdf: default
```

### Example

Here is the source code for a minimal sample document: [template.qmd](template.qmd).

<!-- pdftools::pdf_convert('template.pdf',pages = 1)  --->
![[template.qmd](template.qmd)](template_1.png)

