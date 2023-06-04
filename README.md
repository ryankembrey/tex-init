# tex-init
A shell script that helps the user deploy a LaTeX project


## Usage
* Download the script and add the script to your `$PATH`.
* Create LaTeX templates in `~/templates/latex/tex/`.
* Run the script in the directory you wish to hold your LaTeX project. 
```bash
tex-init
```
When the script is run, a numbered list of all the files in your templates directory
will be shown. Enter the number corresponding to the template you wish to use.
```cli
Available LaTeX templates:
1. article
2. beamer
3. report
Enter the template number:
```
Enter the name of the project.
```cli
Enter the name of the .tex file:
```
The contents created by the script appear in the following tree
```cli
   .
   ├── example_report
   │   ├── figures
   │   ├── sections
   │   └── example_report.tex
```


Additionally, the `-o` and `-op` tags can be placed as an argument when running the script. 
* `-o` automatically opens the `.tex` file in NeoVim once the project is made.
* `-op` automatically opens the `.tex` file in NeoVim, generates the pdf using 
`pdflatex` and opens the pdf in zathura. 
