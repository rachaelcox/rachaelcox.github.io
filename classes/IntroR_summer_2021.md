---
layout: page
title:  "Introduction to R for Biologists, Summer 2021"
date:   2021-06-18 00:00:01
---

This is the homepage for the introductory R course offered by the Big Data in Biology Summer School through the Center for Biomedical Research Support. All lecture slides, coding worksheets and coding worksheet solutions will be posted here. Zoom recordings will be distributed to the class via email. More information regarding summer school courses can be found [here](https://research.utexas.edu/cbrs/classes/big-data-in-biology-summer-school/2021-summer-school/).

------

#### Class information
**Zoom meeting link:**
  * Meeting ID: 946 0259 4373
  * [https://utexas.zoom.us/j/93659263033](https://utexas.zoom.us/j/94602594373)

**Class compute servers (see email for password):**
  * [https://gsafcomp01.ccbb.utexas.edu/](https://gsafcomp01.ccbb.utexas.edu/)
  * [https://gsafcomp02.ccbb.utexas.edu/](https://gsafcomp02.ccbb.utexas.edu/)

These compute servers (aka PODs) are managed by the Biomedical Research Computing Facility. PODs have powerful hardware for handling large data sets, come with many bioinformatics tools pre-installed, are regularly backed up, and feature web-based integrated development environments (IDEs) for both Python and R. You can find out more information about setting up a POD for your own research [here](https://research.utexas.edu/cbrs/cores/cbb/computing-resources/) and [here](https://wikis.utexas.edu/display/RCTFusers). 

------

### Day 1: Introduction to R programming & the Tidyverse
* Slides (R basics): [day1.pdf](/classes/IntroR_2021/slides/day1.pdf)
* Slides (Tidyverse intro): [tidy_intro.pdf](/classes/IntroR_2021/slides/tidy_intro.pdf)
* You can download R from here: [https://cran.r-project.org/](https://cran.r-project.org/)
* You can download RStudio from here: [https://www.rstudio.com/products/rstudio/download/](https://www.rstudio.com/products/rstudio/download/)
* R Markdown basics: [https://rmarkdown.rstudio.com/authoring_basics.html](https://rmarkdown.rstudio.com/authoring_basics.html)
* Tidyverse website, `tidyr` vignettes: [https://tidyr.tidyverse.org/](https://tidyr.tidyverse.org/)
* In-class worksheet 1 (R basics):
    - [R Markdown](/classes/IntroR_2021/worksheets/day1.Rmd)
    - [HTML](/classes/IntroR_2021/worksheets/day1.html)
    - [HTML, Solutions](/classes/IntroR_2021/worksheets/day1_solutions.html)
    - [Test dataset](/classes/datasets/mushrooms_small.csv)
* In-class worksheet 2 (Tidying data):
    - [R Markdown](/classes/IntroR_2021/worksheets/tidying.Rmd)
    - [HTML](/classes/IntroR_2021/worksheets/tidying.html)
    - [HTML, Solutions](/classes/IntroR_2021/worksheets/tidying_solutions.html)
* Blank R Markdown project notebook template:
    - [R Markdown](/classes/files/template.Rmd)
    - [HTML](/classes/files/template.html)

### Day 2: Data visualization with ggplot2
* Slides: [day2.pdf](/classes/IntroR_2021/slides/day2.pdf)
* Tidyverse style guide: [https://style.tidyverse.org/index.html](https://style.tidyverse.org/index.html)
* Tidyverse website, `ggplot2` vignettes: [https://ggplot2.tidyverse.org/](https://ggplot2.tidyverse.org/)
* Guide to all functions available in ggplot2: [https://ggplot2.tidyverse.org/reference/](https://ggplot2.tidyverse.org/reference/#section-aesthetics)
* Default colors that R recognizes: [List of all strings with example output](http://www.stat.columbia.edu/~tzheng/files/Rcolor.pdf)
* Guide to interactive plots using ggplotly: [https://plot.ly/ggplot2/user-guide/](https://plot.ly/ggplot2/user-guide/)
* Optimize your data viz for your data type: [https://serialmentor.com/dataviz/directory-of-visualizations.html](https://serialmentor.com/dataviz/directory-of-visualizations.html)
* In-class worksheet:
    - [R Markdown](/classes/IntroR_2021/worksheets/day2.Rmd)
    - [HTML](/classes/IntroR_2021/worksheets/day2.html)
    - [HTML, Solutions](/classes/IntroR_2021/worksheets/day2_solutions.html)

### Day 3: Data manipulation & analysis with dplyr
* Slides: [day3.pdf](/classes/IntroR_2021/slides/day3.pdf)
* Tidyverse website, `dplyr` vignettes: [https://dplyr.tidyverse.org/](https://dplyr.tidyverse.org/)
* Animated visualizations of different join() functions:
    - [full_join()](https://github.com/corydupai/OCH_codealong/blob/master/animated-full-join.gif)
    - [left_join()](https://github.com/corydupai/OCH_codealong/blob/master/animated-left-join.gif)
    - [inner_join()](https://github.com/corydupai/OCH_codealong/blob/master/animated-inner-join.gif)
    - [anti_join()](https://github.com/corydupai/OCH_codealong/blob/master/animated-anti-join.gif)
* In-class worksheet:
    - [R Markdown](/classes/IntroR_2021/worksheets/day3.Rmd)
    - [HTML](/classes/IntroR_2021/worksheets/day3.html)
    - [HTML, Solutions](/classes/IntroR_2021/worksheets/day3_solutions.html)

### Day 4: Statistics & advanced data analysis
* Slides: [day4.pdf](/classes/IntroR_2021/slides/day4.pdf)
* Hypothesis testing:
    - Choosing a test statistic: [http://www.biostathandbook.com/testchoice.html](http://www.biostathandbook.com/testchoice.html)
    - Generalized hypothesis testing using infer/tidymodels packages: [https://www.andrewheiss.com/blog/2018/12/05/test-any-hypothesis/](https://www.andrewheiss.com/blog/2018/12/05/test-any-hypothesis/)
* Principal component analysis (PCA):
    - Good step-by-step walkthrough of PCA calculations: [https://builtin.com/data-science/step-step-explanation-principal-component-analysis](https://builtin.com/data-science/step-step-explanation-principal-component-analysis)
    - Interactive visualization of principal component analysis (PCA): [http://setosa.io/ev/principal-component-analysis/](http://setosa.io/ev/principal-component-analysis/)
    - Interactive visualization of eigenvectors/eigenvalues if you really want to dig in: [http://setosa.io/ev/eigenvectors-and-eigenvalues/](http://setosa.io/ev/eigenvectors-and-eigenvalues/)
* Clustering:
    - Interactive visualization of k-means clustering: [https://www.naftaliharris.com/blog/visualizing-k-means-clustering/](https://www.naftaliharris.com/blog/visualizing-k-means-clustering/)
    - Towards Data Science article: [The 5 Clustering Algorithms Data Scientists Need to Know](https://towardsdatascience.com/the-5-clustering-algorithms-data-scientists-need-to-know-a36d136ef68)
* In-class worksheet:
    - [R Markdown](/classes/IntroR_2021/worksheets/day4.Rmd)
    - [HTML](/classes/IntroR_2021/worksheets/day4.html)
    - [HTML, Solutions](/classes/IntroR_2021/worksheets/day4_solutions.html)
