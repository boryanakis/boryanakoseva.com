---
date: "2019-05-05T00:00:00+01:00"
draft: false
linktitle: Mac OS
menu:
  blogdown:
    parent: Software
    weight: 1
title: Installation Instructions for Mac OS
toc: true
type: docs
weight: 10
---
  
On a Mac, you will need the following software installed and updated to the most recent versions available:  

***Note***: if installing these software for the first time, please do them in the order in which they are listed.

- [R](https://cran.r-project.org/bin/macosx/)
- [RStudio](https://www.rstudio.com/products/rstudio/download/)
- [Homebrew](https://brew.sh/)  

    To check if you have `Homebrew` installed on your computer, open a Terminal window (Applications :arrow_right: Utilities :arrow_right: Terminal), and type the following at the prompt:

    ```bash 
    brew update
    ```  

    If the command returns a `bash: brew: command not found`, `brew` is not installed on your computer, and you can install it by typing the following command into terminal:
    ```bash
    /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
    ```
    
    If `brew` is installed, the `brew update` command will initiate the update of the software. The update might take a few minutes (or a lot of minutes) depending on how frequently you use/update it. While it is updating, it might seem like terminal is stuck, and towards the end, a number of lines will be printed on your terminal screen. As long as there are no error messages towards the end of the output (and your prompt has returned), you can assume that everything went well. 
  
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
    