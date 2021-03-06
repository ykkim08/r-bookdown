# r-bookdown

CUNY Data 607 Spring 2018 Project

## Project Outline

Using data from the fivethirtyeight Web site (http://fivethirtyeight.com/), our class will develop tutorials to demonstrate the capabilities of the functions in the tidyverse package for R.

Each class member is expected to contribute an example to the final project, which will be compiled in an R bookdown format.  Although each student is expected to prepare a tutorial for a specific function, collaboration on the overall project is encouraged and allowed.

The student body as a whole will be responsible for the organization and content of the project, collaborating in an unsupervised manner to self-determine the best presentation of the final product.

## Project Planning

Please check out the "[Projects](https://github.com/cunydata607/r-bookdown/projects)" tab in GitHub and click on the "[tidyverse r-bookdown project](https://github.com/cunydata607/r-bookdown/projects/1)" and **create a new card to let the group know what you are working on**.  

Also please **add items to the [Book_Structure.md file](https://github.com/cunydata607/r-bookdown/blob/master/Book_Structure.md)** as you choose tidyverse functions that you want to work on.

**Questions and issues** should be added to the [Issues](https://github.com/cunydata607/r-bookdown/issues) tab.

## Working in Github

Github is a web based graphical interface based off of Git: a command line tool for version control. If you're new to Github, learn more through the links below!

For beginners, start here: <https://www.howtogeek.com/180167/htg-explains-what-is-github-and-what-do-geeks-use-it-for/>
And then here: <https://guides.github.com/activities/hello-world/>

> [Github fork and pull request video tutorial:](https://www.youtube.com/watch?v=yr6IzOGoMsQ) https://www.youtube.com/watch?v=yr6IzOGoMsQ

If you're already acquainted with the basics, Github provides tons of training videos on advanced topis here: <https://www.youtube.com/user/GitHubGuides/videos>.

### Working with Bookdown Files

The formatting and structure of the book are created in the index.Rmd file. The filename must remain exactly as index.Rmd or it will not be recognized by bookdown as the index file. The index file should contain setup code and a description of the project only.  Each chapter must be in a separate file in the same R Project in order to 'build' the book using bookdown.  I have already created a file for each chapter.  They must be numbered sequentially (or alphabetically) in order to build in the correct order.  

I have also added code to create a biblilogrpahy in the index file that I copied out of a sample bookdown project.  

To create an inline reference use square brackets and \@R- followed by the package name. The package name must also be added to the bibliography code in the index.Rmd file (if it isn't already there).

For example: 
[@R-tidyr]

The reference will show at the bottom of the page and also at the end in the references chapter.

To learn more about how to work with bookdown you can check out this book written by the package author.  
<https://bookdown.org/yihui/bookdown/>

### Kanban Board (Projects)

### Forking to the Repository

### Adding Contributions to the Repository

## Slack channel communication

Further communication among class members may also be found at https://data607.slack.com in the #tidyversebook channel.
