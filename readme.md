
# Extracting Narratives from Noise

_A Glossary of Journeys in Data Science_

This repository contains data science walkthroughs in each folder demonstrating good practices for
data ingest, normalization, and story telling using the cleaned up data.

Each folder is structured so readers are able to begin following with only beginner level
familiarity with [`python`](https://www.python.org/about/), [`julia`](https://docs.julialang.org/en/v1/),
or [`r`](https://www.r-project.org/about.html)/[`rscript`](https://www.rdocumentation.org/packages/utils/versions/3.6.2/topics/Rscript).

Very few external libraries will be used; when beginning it harms understanding of underlying data to pass it into `magic_func(x)`
then test the resulting data to determine if the `magic_func` actually did what you wanted. We will flip this around and write many of our
own `magic_func()`-tions by first considering what question is being answered, which leads to raw data sets, and in between there is much
normalization required which creates room for unecessary complexity to grow.

When we do use external libraries the reasons for the choice will be laid out and management of the libraries will be done
such that even if the library behavior/interface changes we can continue using it without signficant changes to **our** code.

## [`airy-appreciation`](./airy-appreciation)

In this folder we use public data sets to answer these two questions

 - What is the correlation between dollars invested in an airline and the airline's average flight delay in minutes?
 - How much time passes between time-of-investment and observed effects on the airline's average flight delay?













