# Setting up R

```
sudo apt-get install libfreetype6-dev libpng-dev libtiff5-dev libjpeg-dev

if (!requireNamespace("devtools")) install.packages('devtools')
devtools::install_github('rstudio/bookdown')

install.packages("servr")

cd tdlbook
rstudio tdlbook.Rproj

bookdown::serve_book()

# install.packages("rsconnect")

# bookdown::publish_book()

install.packages("usethis")

library(usethis)

use_github_action("bookdown.yaml")

install.packages("renv")

library(renv)

renv::snapshot()
```

# Useful links

- https://yihui.org/en/2018/08/bookdown-crc/
- https://www.chapmanhall.com/stats/contact.html
- https://pkgs.rstudio.com/bookdown/articles/bookdown.html
- https://bookdown.org/yihui/bookdown/
- https://f0nzie.github.io/yongks-python-rmarkdown-book/index.html
- https://stackoverflow.com/questions/73843166/syntax-highlighting-using-python-in-bookdown
- https://github.com/christophM/interpretable-ml-book
- https://emilhvitfeldt.com/post/bookdown-netlify-github-actions/#create-github-workflow
- https://github.com/hadley/r-pkgs/blob/main/.github/workflows/render.yaml
- https://www.youtube.com/watch?v=_ptrgqx2zUs
- https://posit.cloud/
