# assignment-plate
A simple Latex template for witten assigments

## Usage
- Clone the repository

- make sure you have the appropriate LaTeX packages for you needs installed

- Link your body `.tex` file to `current.tex`. 
```bash
ln -sf path/to/your/file.tex
```

- compile you LaTeX document: 
```bash
latexmk -pdf skeleton.tex -jobname="name for your pdf"
```

Enjoy! :)
