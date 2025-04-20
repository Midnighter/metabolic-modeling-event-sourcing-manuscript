# In Pursuit of Total Reproducibility

This repository contains the sources for the paper ["In Pursuit of Total
Reproducibility"](https://arxiv.org/abs/2504.11635).

## Compilation

The main text can be found in `event-sourcing-systems-biology.qmd`. To compile
the document, you need to have Quarto installed. You can install it from
[here](https://quarto.org/docs/get-started/). The document is configured to be
compiled to either HTML

```sh
quarto render event-sourcing-systems-biology.qmd --to html
```

or PDF.

```sh
quarto render event-sourcing-systems-biology.qmd --to pdf
```

Some of the images are generated from PlantUML sources. To generate the images
you can either use an online server or, for example, the PlantUML VS Code
extension.

### arXiv

For the arXiv submission, the sources were prepared in the following way:

1. Generate the PDF as above.
2. Copy the `.tex` file to `arxiv.tex`.
3. Remove the nesting for any references to the images in the `.tex` file.
4. Upload the modified `.tex` file and the images to arXiv.

## Copyright

<a href="https://creativecommons.org/licenses/by-sa/4.0/">
<img src="images/cc-by-sa.png" alt="CC BY-SA 4.0" height="20" />
</a>

This work is licensed under the [Creative Commons Attribution-ShareAlike 4.0
International License](https://creativecommons.org/licenses/by-sa/4.0/). To view
a copy of this license, visit
[https://creativecommons.org/licenses/by-sa/4.0/](https://creativecommons.org/licenses/by-sa/4.0/)
or send a letter to Creative Commons, PO Box 1866, Mountain View, CA 94042, USA.
