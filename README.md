Intro to R, 2019 Spring
================
John Little & Joel Herndon
2019-03-19

<!-- Edit the README.Rmd.  Readme.md is auto genererated -->
README
======

-   Code

    -   Part 1: [dplyr](01_dplyr.Rmd) -- data transformations
    -   Part 2: [ETD/Join](02_join-skim-eda.Rmd) -- exploratory data transformations & skimr
    -   Part 3: [**Brief** introduction to ggplot2](https://intro2r.library.duke.edu/visualization.html)
    -   Part 4: [Importing Large Files](large_data.Rmd)
    -   Part 5: [**Brief** GIS/Mapping](https://intro2r.library.duke.edu/gis.html)

-   Repo -- Intro2R repo

    -   <https://is.gd/intro2r_2019spring>

    -   Rstudio.cloud: <https://is.gd/rdatafest>

This repository contains supporting datasets and files for our [*Intro to R*](https://intro2r.library.duke.edu/) workshop by the [Data & Visualization Services Department](http://library.duke.edu/data), Duke University Libraries. You can find more information about our future and past [workshops](http://library.duke.edu/data/news)

-   Our *guide* can be found at our [Rfun site](https://intro2r.library.duke.edu/)

-   More on R [(then, scroll down to "R Learning Resources".) Includes video captures](https://library.duke.edu/data/guides)

Workshop Outline
----------------

1.  Download the zipped repository ![Download ZIP button](images/clone.png "Download ZIP button")

    -   If using [RStudio.cloud](https://rstudio.cloud/) or the [Duke Docker instance](https://vm-manage.oit.duke.edu/containers/rstudio), use the `upload` button witin the **Files** tab to uplaod the zipped folder (which is the functional equivalent of the next two steps.)

2.  Unzip/expand the zipped repo as a folder **in your Documents Directory**
3.  Launch RStudio
4.  File &gt; New Project...
5.  Existing Directory: Browse to your unzipped copy in the documents directory

    1.  Literate Coding: brief explanation
        1.  New Code Chunk: *Ctrl+Alt+I*
        2.  R Markdown: brief explanation
    2.  [`library(tidyverse)`](https://tidyverse.org)

6.  Load & View Tibble (data frame)

7.  Data Structure & Data Types (brief)

8.  [`dplyr`](http://dplyr.tidyverse.org/) -- part of tidyverse

    1.  `filter` rows
    2.  `arrange` rows by variables
    3.  `select` columns
    4.  `mutate` derive cells / new variables
    5.  `count` column totals
    6.  `summarize` grouping reports

9.  **Now You Try It.** Hands on exercises.

    1.  [exercise\_01.Rmd](exercise_01.Rmd)
    2.  [exercise\_02.Rmd](exercise_02.Rmd)
    3.  [answers.Rmd](answers.Rmd)

10. Basic Exploratory Data Analysis

    1.  Read in new datasets
    2.  `library(skimr)`

11. More `dplyr` -- join two datasets

    1.  `left_join` to merge data

12. Basic Visualization with `ggplot2`

    1.  Basic visualization (Scatter Plot, Box Plot, Histogram, Bar Chart)
    2.  Take the ggplot2 workshop, or see the [materials](https://github.com/amzoss/ggplot2-S19b)
    3.  Resource: <https://rfun.library.duke.edu/portfolio/ggplot_workshop/>

13. Our Training Materials

    1.  R we having fun yet‽ <https://rfun.library.duke.edu>. Training materials for R.

    2.  Full DVS [workshop series](https://library.duke.edu/data/news/past-workshops)

14. Questions: [Walk-in schedule](https://library.duke.edu/data/about/schedule) and by appointment [Data Science Consulting](https://library.duke.edu/data/about)

License
-------

Shareable via Creative Commons: [CC-BY-NC](https://creativecommons.org/licenses/by-nc/4.0/)<br> <img src="images/by-nc.png" alt="&quot;CC BY-NC&quot;" height="30" />
