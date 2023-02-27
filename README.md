# fairlie
Stata module to compute nonlinear decomposition of binary outcome differentials

`fairlie` computes the nonlinear decomposition of binary outcome differentials
proposed by Fairlie ([1999](https://doi.org/10.1086/209914),
[2005](https://doi.org/10.3233/JEM-2005-0259)).

To install `fairlie` from the SSC Archive, type

    . ssc install fairlie, replace

To install `fairlie` from GitHub, type

    . net install fairlie, replace from(https://raw.githubusercontent.com/benjann/fairlie/main/)

---

Main changes:

    27feb2023
    - released on github

    16jun2008
    - fixed typo in output: "N of obs G=0"=>"N of obs G=1"

    20may2008
    - bug fixed related to -mata strofreal()- and -set dp-

    19may2008
    - weights now allowed
    - returns now in e(); saveest() option to save model
    - new syntax for specifying regressor sets
    - legend for regressor sets (suppress using -nolegend- option)
    - -fairlie- now redisplays results

    13feb2008:
    - r(N0), r(N1) added and displayed
    - homecomp.dta added to package

    13feb2007
    - -ro- option added

    08may2006
    - first published on SSC


