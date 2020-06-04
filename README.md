autotex is a simple command line tool for rapidly initializing and compiling LaTeX documents
```markdown
/some_path$ autotex -f 
```
To install, make a symbolic link in /bin/ to autotex and chmod autotex. Currently assumes that the user has vim and evince installed. 

```markdown
usage: autotex [-h] [-a ARTICLE] [-b BEAMER] [-l LETTER] [-f] [-r] [-e] [-i]

optional arguments:
  -h, --help			show this help message and exit
  -a, --article 		creates a TeX file using the article class
  -b, --beamer			creates a TeX file using the beamer class
  -l, --letter 			creates a TeX file using the letter class
  -f, --full			compiles a TeX file using the full class
  -r, --refs			compiles a TeX file using the refs class
  -e, --easy			compiles a TeX file using the easy class
  -i, --hide			don't display pdf after compilation
```
