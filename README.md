# fa-mask
Masks specified regions in FASTA sequences

##Author

Jason Kwong (@kwongjc)

##Dependencies
* Python 2.7.x
* BioPython

##Usage

```
$ fa-mask.py -h
usage: 
  fa-mask.py --regions <FILE> FASTA > masked.fa

Script to mask specified regions in FASTA sequence

positional arguments:
  FASTA           FASTA sequence to modify (required)

optional arguments:
  -h, --help      show this help message and exit
  --regions FILE  Tab-separated file with 3 columns: LOCUS START END (BED format) (required)
  --mask N        Symbol to use for masking regions (default = "N").
                  Use "--mask lc" to perform soft masking in lower case
  --out FILE      Output file for new genome (optional - otherwise will print to stdout)
  --version       show program's version number and exit
```

##Bugs

Please submit via the [GitHub issues page](https://github.com/kwongj/fa-mask/issues).  

##Software Licence

[GPLv3](https://github.com/kwongj/fa-mask/blob/master/LICENSE)
