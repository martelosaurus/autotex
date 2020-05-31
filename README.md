autotex is a simple command line tool for rapidly initializing and compiling LaTeX documents
```markdown
/some_path$ autotex -f 
```
To install, make a symbolic link in /bin/ to autotex and chmod autotex. Currently assumes that the user has vim and evince installed. 

```markdown
usage: autotex [-h] [-a ARTICLE] [-b BEAMER] [-l LETTER] [-f] [-r] [-e] [-i]

optional arguments:
  -h, --help            show this help message and exit
  -a, --article 		Creates a TeX file using the article class
  -b, --beamer 			Creates a TeX file using the beamer class
  -l, --letter 			Creates a TeX file using the letter class
  -f, --full            Compiles a TeX file using the full class
  -r, --refs            Compiles a TeX file using the refs class
  -e, --easy            Compiles a TeX file using the easy class
  -i, --hide            Don't display pdf after compilation
```
