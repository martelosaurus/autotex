autotex is a simple command line tool for rapidly initializing and compiling LaTeX documents. Currently, it's more of a learning project so that I can write CLIs in the future. 

To install, make a symbolic link in /bin/ to autotex and chmod autotex. Currently assumes that the user has vim and evince installed. 

```markdown
usage: autotex [-h] [-a _] [-b _] [-l _] [-e] [-r] [-f] [-i] [-d]

A command line tool for creating and compiling TeX files

optional arguments:
  -h, --help         show this help message and exit
  -a _, --article _  creates a TeX file using the article class
  -b _, --beamer _   creates a TeX file using the beamer class
  -l _, --letter _   creates a TeX file using the letter class
  -e, --easy         compiles using the 'easy' sequence (see --docs)
  -r, --refs         compiles using the 'refs' sequence (see --docs)
  -f, --full         compiles using the 'full' sequence (see --docs)
  -i, --hide         don't display pdf after compilation
  -d, --docs         displays additional info on compilation sequences
```
