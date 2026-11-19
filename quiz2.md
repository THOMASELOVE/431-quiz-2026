# Quiz 2 Information

All links to Quiz 2 materials will be posted to this page by **Friday 2026-11-20 at 5 PM**.

## Quiz Materials

1. The Quiz will be provided to you on this page as a **29-page** PDF document, which includes detailed instructions.
2. I am providing **two** data sets (called **cats1.xlsx** and **q28_data.csv** that are mentioned in the Quiz. These can either be downloaded from [our 431-data page](https://github.com/THOMASELOVE/431-data), or found in our Shared Drive in the **431 Quiz 2** folder's data sub-folder.
3. You will provide your responses using [this Google Form Answer Sheet](https://tinyurl.com/431-2026-quiz2-form), as you did in Quiz 1. The link to the form is <https://tinyurl.com/431-2026-quiz2-form>.

## R packages code chunk

Here is the code chunk listing R packages from page 6 of the Quiz 2 Instructions, so you can copy and paste it into RStudio.

```{r}
#| message: false

knitr::opts_chunk$set(comment = NA)

library(here)
source(here("data/Love-431.R"))

library(broom) 
library(car) 
library(DescTools) 
library(Epi) 
library(GGally)
library(gt)
library(glue)
library(janitor)
library(naniar)
library(mice) 
library(MKinfer)
library(olsrr)
library(patchwork)
library(pwr)
library(readxl) 
library(rstanarm)
library(easystats)
library(tidyverse)

theme_set(theme_bw())
```

## Quiz 2 is due at **4 PM on Monday 2026-11-30**.

## Thanksgiving Week

- We will not hold 431 class on either Tuesday 2026-11-24 or Thursday 2026-11-26.
- TA office hours will be **closed** from Saturday 2026-11-21 through Friday 2026-11-27, returning Saturday 2026-11-28.
- 431-help will also be **closed** from Monday 2026-11-23 through Friday 2026-11-27, and Dr. Love will not be answering email during that time.

