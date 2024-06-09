```
sudo apt-get install libfreetype6-dev libpng-dev libtiff5-dev libjpeg-dev

if (!requireNamespace("devtools")) install.packages('devtools')
devtools::install_github('rstudio/bookdown')

install.packages("servr")

cd tdl_book_bookdown
rstudio tdl_book.Rproj

bookdown::serve_book()

# install.packages("rsconnect")

# bookdown::publish_book()

install.packages("usethis")

library(usethis)

use_github_action("bookdown.yaml")
```

