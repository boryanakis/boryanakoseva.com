---
date: "2019-05-05T00:00:00+01:00"
draft: false
linktitle: Windows
menu:
  blogdown:
    parent: Software
    weight: 2
title: Installation Instructions for Windows
toc: true
type: docs
weight: 20
---
  
On a Windows, you will need the following software installed and updated to the most recent versions available:  

***Note***: if installing these software for the first time, please do them in the order in which they are listed.

- [R](https://cran.r-project.org/bin/windows/base/)
- [Rtools](https://cran.r-project.org/bin/windows/Rtools/)  
    Download and install the recommended version of the software. 
- [Git Bash](https://gitforwindows.org/)  
    Use the default settings during installation.
- [RStudio](https://www.rstudio.com/products/rstudio/download/)
- [blogdown](https://bookdown.org/yihui/blogdown/)

    To install `blogdown` and its dependencies, open RStudio and type the following into the console:
    
    ```
    install.packages("blogdown", dependencies = TRUE)
    ```  

- [Hugo](https://gohugo.io/)  

    The easiest way to install `Hugo` is through `blogdown`. In RStudio, execute the following command:

    ```
    blogdown::install_hugo()
    ```   

- [GitHub](https://github.com/)

    This is not an installation as much as it is a reminder that you need to have a Github account and to know your password. 
    