# tex-init
A shell script for creating LaTeX projects

## Overview
`tex-init` is a convenient shell script that helps you create LaTeX projects with ease. It allows you to choose from a collection of pre-defined LaTeX templates and sets up the project structure for you.

## Prerequisites
Before using `tex-init`, make sure you have the following:

- LaTeX distribution installed on your system.
- A directory named `tex` under `~/templates/latex` that contains your LaTeX templates.

## Usage
1. Download the `tex-init` script and add it to a directory included in your `$PATH`.
2. Open your terminal and navigate to the directory where you want to create your LaTeX project.
3. Run the following command:
```bash
    tex-init
```
4. You will see a numbered list of available LaTeX templates. Enter the number corresponding to the template you want to use.
5. Enter the name of your LaTeX project.
6. The script will create the necessary directories and generate the main `.tex` file based on the selected template.
7. You will see the project structure displayed in a tree-like format:
```bash
└── example
    ├── bib
    │   └── bibliography.bib
    ├── coversheet
    │   ├── coversheet.pdf
    │   ├── coversheet.tex
    │   └── logo.png
    ├── example.pdf
    ├── example.tex
    ├── figures
    │   ├── logo.png
    │   └── title_image.png
    └── sections
        ├── preamble.tex
        └── titlepage.tex
```
This represents the directory structure of your LaTeX project.

---
Remember to customize your LaTeX templates in the `~/templates/latex/tex` directory to suit your needs.

Feel free to modify and enhance the script according to your requirements.
