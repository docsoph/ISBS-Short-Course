Functional Data Analysis in Sports Biomechanics
================

<center>

![](logo/ISBS-Logo-2024.png) ![](logo/whitespace.png)
![](logo/fda-logo.png)

</center>

------------------------------------------------------------------------

# Welcome

This is the web page for the [ISBS 2024](https://www.isbs2024.com)
pre-conference workshop [***“Functional Data Analysis in Sports
Biomechanics”***](https://www.isbs2024.com/wp-content/uploads/2024/03/Pre-workshop_FDA.pdf),
delivered by [Prof. Drew Harrison (University of
Limerick)](https://www.ul.ie/shprc/professor-drew-harrison) and
[Dr. Edward Gunning (University of
Pennsylvania)](https://edwardgunning.github.io/).

------------------------------------------------------------------------

# 🖥 Computing Pre-requisites

## R and RStudio

You should bring your own laptop with the following software installed:

- **The R Language for Statistical Computing**
  - It can be downloaded from <https://cloud.r-project.org>
  - For further assistance see [this video by RStudio
    education](https://vimeo.com/203516510)
- **The RStudio Integrated Development Environment (IDE)**
  - It can be downloaded from <https://posit.co/>
  - For further assistance see [this video by RStudio
    education](https://vimeo.com/203516510) (**Note**: The RStudio
    company has changed to Posit PBC, so there may be some minor
    differences)

**Note**: If you are unable to install R and RStudio, you can work with
a free, lite web version of RStudio called [*posit
cloud*](https://posit.cloud/). Watch [this video from Posit
PBC](https://www.youtube.com/watch?v=-fzwm4ZhVQQ) to set up an account
and get started.

We also recommend setting up an RStudio project to work and store your
files for this workshop in – see [this helpful guide on setting up
projects by Posit
PBC](https://support.posit.co/hc/en-us/articles/200526207-Using-RStudio-Projects).

**IMPORTANT**: **We do not require any previous knowledge of R
programming or FDA**. We have structured the lecture and practical
sessions in such a way that all levels of experience will be catered
for. However, if interested, our favourite (free!) resources for getting
up to speed with R are:

- [R for Data Science (2nd Edition)](https://r4ds.hadley.nz/) by Hadley
  Wickham, Mine Çetinkaya-Rundel, and Garrett Grolemund.

- [R Programming for Data
  Science](https://bookdown.org/rdpeng/rprogdatascience/) by Roger D.
  Peng.

## R Packages

For this workshop, we will primarily use the `fda` (Ramsay, Graves and
Hooker, 2024) and `refund` (Goldsmith et al., 2024) packages.

To install these, you should run the following commands:

``` r
install.packages("fda") # install the fda package
install.packages("refund") # install the refund package
```

------------------------------------------------------------------------

# 📒 Material

- **Lecture Slides** (these MS Powerpoint slides will not preview in
  GitHub, so you will need to click the ![](logo/download-raw-file.png)
  icon on the top right to download):
  - [Welcome and introduction](slides/01-welcome.pptx)
  - [Part 1 – Data representation and
    smoothing](slides/02-smoothing.pptx)
  - [Part 2 – Registration](slides/03-registration.pptx)
  - [Part 3 – Functional Principal Components Analysis
    (FPCA)](slides/04-fpca.pptx)
  - [Part 4 – Functional regression](slides/05-fregression.pptx)
- **Practical Material**:
  - [Part 1 – Data representation and
    smoothing](practicals/01-smoothing.md)
  - [Part 2 – Registration](practicals/02-registration.md)
  - [Part 3 – Functional Principal Components Analysis
    (FPCA)](practicals/03-fpca.md)
  - [Part 4 – Functional regression (in
    progress)](practicals/04-functional-regression.md)
- **Discussion/ Q&A**:
  - [List of potential discussion
    topics](slides/discussion-q-and-a.pptx)

------------------------------------------------------------------------

# 🏢 Location

The workshop will take place in Grüner Hörsaal.

------------------------------------------------------------------------

# ⏱️ Schedule

We will meet at the venue from the official start time of 8.30am, for a
start at 9.00am.

|              Time | Topic                    | Format                |  Lead   |
|------------------:|:-------------------------|-----------------------|:-------:|
| $09.00$ - $09.30$ | Welcome and Introduction | Lecture               |   DH    |
| $09.30$ - $09.50$ | Coffee Break             |                       |         |
| $09.50$ - $12.00$ | Foundations of FDA       | Lecture               | DH & EG |
| $12.00$ - $13.00$ | Lunch                    |                       |         |
| $13.00$ - $15.00$ | Hands-on FDA with **R**  | Practical (groups)    |   EG    |
| $15.00$ - $16.00$ | Q&A with Coffee          | Group Discussion/ Q&A | DH & EG |

------------------------------------------------------------------------

# 📧 Contact

- Queries about registration for the course should be sent to the ISBS
  2024 organisers.

- Queries about the course material should be sent to
  <edward.gunning@pennmedicine.upenn.edu> with the subject line *“ISBS
  pre-conference workshop material”*.

------------------------------------------------------------------------

# 📚 References

- J. O. Ramsay, Spencer Graves and Giles Hooker (2024). fda: Functional
  Data Analysis. R package version 6.1.8.
  <https://CRAN.R-project.org/package=fda>

- Jeff Goldsmith, Fabian Scheipl, Lei Huang, Julia Wrobel, Chongzhi Di,
  Jonathan Gellar, Jaroslaw Harezlak, Mathew W. McLean, Bruce Swihart,
  Luo Xiao, Ciprian Crainiceanu and Philip T. Reiss (2024). refund:
  Regression with Functional Data. R package version 0.1.35.
  <https://CRAN.R-project.org/package=refund>

------------------------------------------------------------------------

# 📖 Further Reading

- A deeper account of this material will be provided in our upcoming
  book [Functional Data Analysis in
  Biomechanics](https://link.springer.com/book/9783031688614) which will
  be published by Springer later this year

<center>
<img src="logo/book-cover.png" width="150">
</center>

- Crainiceanu, C. M., Goldsmith, J., Leroux, A., & Cui, E. (2024).
  Functional Data Analysis with R (1st edition). Chapman and Hall/CRC
  (book website: <https://functionaldataanalysis.org>)

- Ramsay, J. O., & Silverman, B. W. (2005). Functional Data Analysis
  (2nd ed.). Springer-Verlag. <https://doi.org/10.1007/b98888>

- Ramsay, J. O., Hooker, G., & Graves, S. (2009). Functional Data
  Analysis with R and MATLAB. Springer-Verlag.
  <https://doi.org/10.1007/978-0-387-98185-7>

- [CRAN Task View: Functional Data
  Analysis](https://cran.r-project.org/web/views/FunctionalData.html)

------------------------------------------------------------------------

# 💾 Software Information (Reproducibility)

``` r
R.version # version of R
```

    ##                _                           
    ## platform       x86_64-apple-darwin17.0     
    ## arch           x86_64                      
    ## os             darwin17.0                  
    ## system         x86_64, darwin17.0          
    ## status                                     
    ## major          4                           
    ## minor          1.2                         
    ## year           2021                        
    ## month          11                          
    ## day            01                          
    ## svn rev        81115                       
    ## language       R                           
    ## version.string R version 4.1.2 (2021-11-01)
    ## nickname       Bird Hippie

``` r
# package versions:
packageVersion("fda") 
```

    ## [1] '5.5.1'

``` r
packageVersion("refund")
```

    ## [1] '0.1.26'

``` r
sessionInfo() # R session info.
```

    ## R version 4.1.2 (2021-11-01)
    ## Platform: x86_64-apple-darwin17.0 (64-bit)
    ## Running under: macOS Big Sur 10.16
    ## 
    ## Matrix products: default
    ## BLAS:   /Library/Frameworks/R.framework/Versions/4.1/Resources/lib/libRblas.0.dylib
    ## LAPACK: /Library/Frameworks/R.framework/Versions/4.1/Resources/lib/libRlapack.dylib
    ## 
    ## locale:
    ## [1] en_IE.UTF-8/en_IE.UTF-8/en_IE.UTF-8/C/en_IE.UTF-8/en_IE.UTF-8
    ## 
    ## attached base packages:
    ## [1] stats     graphics  grDevices utils     datasets  methods   base     
    ## 
    ## loaded via a namespace (and not attached):
    ##  [1] compiler_4.1.2  fastmap_1.1.0   cli_3.6.1       tools_4.1.2    
    ##  [5] htmltools_0.5.5 rstudioapi_0.13 yaml_2.3.5      rmarkdown_2.27 
    ##  [9] knitr_1.47      xfun_0.44       digest_0.6.29   mime_0.12      
    ## [13] rlang_1.1.1     evaluate_0.15
