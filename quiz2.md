# Quiz 2 Information

- All links to Quiz 2 materials will be posted to this page by **Thursday 2026-11-19 at 5 PM**.
- Quiz 2 is due at **4 PM on Monday 2026-11-30**.

## Quiz Materials

1. The Quiz will be provided to you on this page as a **29-page** PDF document, which includes detailed instructions, and all 30 questions.
    - In addition, there are two bonus questions (clearly marked as bonus) at the end of the Quiz.
    - Neither will improve your Quiz grade. Each will improve your end-of-semester bonus if you build a good response.
    - It's your choice to do both, either or none of the bonus questions.
2. I have provided **two** data sets (called **cats1.xlsx** and **q28_data.csv** that are mentioned in the Quiz. These can either be downloaded from [our 431-data page](https://github.com/THOMASELOVE/431-data), or found in our Shared Drive in the **431 Quiz 2** folder's data sub-folder.
3. You will provide your responses using [this Google Form Answer Sheet](https://tinyurl.com/431-2026-quiz2-form), as you did in Quiz 1. The link to the form is <https://tinyurl.com/431-2026-quiz2-form>.

---------

## Thanksgiving Week Reminders

- We will not hold 431 class on either Tuesday 2026-11-24 or Thursday 2026-11-26.
- TA office hours are **closed** from Saturday 2026-11-21 through Friday 2026-11-27, returning Saturday 2026-11-28.

## Getting Help

During the Quiz period (5 PM 2026-11-19 through 4 PM 2026-11-30) we will not answer questions about the Quiz in TA office hours, or in any other way. Some cautions:

- I **do not guarantee** to answer email I receive from Monday 2026-11-23 through Saturday 2026-11-28 **until** Sunday 2026-11-29.
- Specific questions are more likely to get helpful answers.
- I will not review your code or your English for you.
- I will not tell you if your answer is correct, or if it is complete.
- I will email all students **on Sunday 2026-11-29** if we find an error in the Quiz that needs fixing between now and then.

## Special Instructions for Quiz 2

**Unless otherwise specified in the Question**, do the following on Quiz 2:

- Any time you need to **set a random seed**, set it to `4312026`, please.
- All uncertainty intervals you develop for this Quiz should use **89%** as their confidence level. 
- Round all answers to 2 decimal places.
- Use 1,000 replications any time you use a bootstrap.
- Do not include the `library` command at any time for your responses on the Quiz that ask for code. 
- Occasionally, we ask you to provide a single line of code. If not otherwise specified, a single line of code in response can contain **at most** three pipes, although you may or may not need the pipe in any particular setting. I exclusively used the `|>` pipe, and not the `%>%` pipe, in developing this Quiz, but you may use either.
- Assume in all questions that all packages listed below are loaded in R.

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

