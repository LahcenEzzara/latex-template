# Simple LaTeX Academic Template

A clean, straightforward LaTeX template for academic reports, theses, and dissertations. This template uses a single-file approach for simplicity while maintaining professional formatting and all essential academic document features.

## Features

- 📄 **All-in-one file**: Everything in a single `main.tex` file for easy editing.
- 📚 **Complete structure**: Ready-made chapters and sections for academic documents.
- 🔍 **Clean typesetting**: Professional margins, spacing, and typography.
- 📊 **Built-in examples**: Sample figures, tables, equations, and code listings.
- 📝 **Bibliography support**: BibTeX integration for references.
- 📘 **Academic focus**: Designed specifically for reports and theses.
- ⚠️ **Error-free**: Pre-configured to avoid common LaTeX warnings and errors.

## Requirements

- A LaTeX distribution (TeXLive, MiKTeX, or MacTeX).
- A text editor or LaTeX editor.

## Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/LahcenEzzara/latex-template.git
   cd latex-template
   ```

2. Open `main.tex` in your preferred LaTeX editor.

3. Edit the title, author, and other details at the top of the file.

4. Add your content to each chapter section.

5. Compile the document using your LaTeX editor or command-line tools.

## Compilation

You can compile the document using one of these methods:

### Using Command Line
```bash
# Full compilation with bibliography
pdflatex main
bibtex main
pdflatex main
pdflatex main
```

### Using LaTeX Editors
Most LaTeX editors (TeXstudio, TeXmaker, Overleaf, etc.) have one-click compilation buttons that will handle the process for you.

## Customization

The template is designed to be easy to customize:

- **Title & Author**: Edit the `\title{}` and `\author{}` commands.
- **Margins**: Modify the `\geometry{margin=2.5cm}` parameter.
- **Line spacing**: Change `\onehalfspacing` to `\doublespacing` or `\singlespacing`.
- **Colors**: Adjust the `\hypersetup` block for link colors.
- **Headers/Footers**: Customize the `\fancyhead` and `\fancyfoot` commands.
- **Float positioning**: Adjust the `[htbp]` specifiers for figures and tables.

## Technical Details

This template includes several optimizations to provide a smooth LaTeX experience:

- **Fixed header height**: Properly configured `\headheight` (14.5pt) to avoid `fancyhdr` warnings.
- **Proper float positioning**: Uses `[htbp]` positioning for figures and tables to prevent LaTeX float warnings.
- **Balanced margins**: Properly configured for academic documents.
- **Compatible bibliography setup**: Supports both BibTeX and inline bibliography options.

## Bibliography

The template uses BibTeX for reference management. You have two options:

1. Create a separate `references.bib` file with your BibTeX entries.
2. Use the inline bibliography with the `\begin{thebibliography}` environment at the end of the file.

## License

This template is available under the MIT License. See the `LICENSE` file for details.