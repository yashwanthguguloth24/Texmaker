Assuming Texmaker is already installed. This repository has the commands to compile a tex file using texmaker in terminal.

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


We can updates the changes in the github repository using the following commands

1.Clonning the repository 

```
clone "repository link"
```
2.Adding 

```
git add .                 
```                                                 

3. Commit 
```
git commit -m "first commit"                 
```

4.Finally push the changes 
```
git push
```




