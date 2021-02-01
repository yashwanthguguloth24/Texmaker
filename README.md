Assuming Texmaker is already installed. This repository has the commands to compile a tex file using taxmaker in terminal.

First create a .tex file . Then open the terminal with the directory of .tex file 

Example file : ee18btech11017.tex

Type 


```
latex ee18btech11017.tex
```

Then type

```
dvips ee18btech11017.dvi
```

Finally,

```
ps2pdf ee18btech11017.ps
```

This creates the ee18btech11017.pdf file in the same directory
