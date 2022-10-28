--- 
title: "Analysis"
author: "Phil McAleer, Carolina E. Kuepper-Tetzel, Helena Paterson"
date: "2022-02-23"
site: bookdown::bookdown_site
documentclass: book
bibliography: [book.bib, packages.bib]
csl: include/apa.csl
link-citations: yes
description: |
  This book covers data skills such as R Markdown, data wrangling with tidyverse, and data visualisation with ggplot2. It also introduces statistical concepts such as permutation tests, NHST, alpha, power, effect size, and sample size as well as statistical procedures such as correlations and the general linear model.
url: https://psyteachr.github.io/analysis-v2
github-repo: psyteachr/analysis-v2
cover-image: images/logos/logo.png
apple-touch-icon: images/logos/apple-touch-icon.png
apple-touch-icon-size: 180
favicon: images/logos/favicon.ico
---

# Overview {-}

Placeholder



<!--chapter:end:index.Rmd-->


# Starting with R Markdown

Placeholder


## Overview
### What is R Markdown?
### Advantages of using R Markdown
### Creating an R Markdown (.Rmd) File
### One last thing before beginning!

<!--chapter:end:01-s01-lab01a.Rmd-->



## R Markdown Basics
### Create a new R Markdown document
### Code Chunks
### Knitting Code
### Adding Code Chunk Rules and Options
### Adding Inline Code
### Formatting the R Markdown File

<!--chapter:end:01-s01-lab01b.Rmd-->



## R Markdown Application
### R Markdown and The Experimental Design Portfolio
### The Ponzo Illusion and Age
### Task 1: Setting up Your R Markdown Portfolio {#Ch1InClassQueT1}
### Task 2: Give your Report a Heading {#Ch1InClassQueT2}
### Task 3: Creating a Code Chunk {#Ch1InClassQueT3}
### Task 4: Writing your Report {#Ch1InClassQueT4}
### Task 5: Making Text Bold or Italicized {#Ch1InClassQueT5}
### Task 6: Adding Links to the Data in your Methods {#Ch1InClassQueT6}
### Task 7: Adding an Image to your Methods {#Ch1InClassQueT7}
### Task 8: Adding a Table to your Results {#Ch1InClassQueT8}
### Task 9: Adding a Figure to your Results {#Ch1InClassQueT9}

<!--chapter:end:01-s01-lab01c.Rmd-->

## Practice Your Skills

This is a brief exercise for you to practice the skills taught in this chapter. In future assignments we will ask you to do some coding and interpretation, but for this exercise we just want you to familiarise yourself again with working with .Rmd files.

We have set up this task so that you can practice 1) downloading the assignment files, 2) renaming the files, 3) editing the .Rmd file, and 4) saving the edited .Rmd file. 

**Download the files**

You will first need to download the file from the zip folder on Moodle and then open it in R through RStudio. For this exercise, you can also download [the ZIP file here](data/01-s01/GUID_L2_Ch1_PracticeSkills.zip).

Simply follow the instructions in the .Rmd document that you will find in the ZIP file. Enjoy!

<!--chapter:end:01-s01-lab01d.Rmd-->



## Solutions to Questions
### Task 2: Give your Report a Heading
### Task 3: Creating a Code Chunk
### Task 4: Writing your Report
### Task 5: Making Text Bold or Italicized
### Task 6: Adding Links to the Data in your Methods
### Task 7: Adding an Image to your Methods
### Task 8: Adding a Table to your Results
### Task 9: Adding a Figure to your Results
### Example of output after completing all activities
#### The Magnitude of the Ponzo Illusion Varies as a Function of Age {-}
#### Introduction {-}
#### Methods {-}
##### Data {-}
##### Stimuli {-}
#### Results {-}

<!--chapter:end:01-s01-lab01e.Rmd-->


# Data-Wrangling: A Key Skill

Placeholder


## Overview

<!--chapter:end:02-s01-lab02a.Rmd-->



## Data Wrangling Basics
### Revisiting the Wickham Six
### Learning to Wrangle
### **`select()`** Function - keep only specific columns {#Ch2PreClassQueT1}
### **`arrange()`** Function - sort and arrange columns {#Ch2PreClassQueT2}
### **`filter()`** Function - keep only parts of the data {#Ch2PreClassQueT3}
### **`mutate()`** Function - add new columns {#Ch2PreClassQueT4}
### **`group_by()`** Function - group parts of data together {#Ch2PreClassQueT5}
### **`summarise()`** Function - do some calculations on the data {#Ch2PreClassQueT6}
### Other Useful Functions: `bind_rows()` and `count()`
### Pipes (**`%>%`**) - make your code efficient

<!--chapter:end:02-s01-lab02b.Rmd-->



## Data Wrangling Application
### Task 1: Open a Script
### Task 2: Bring in Your Library {#Ch2InClassQueT2}
### Task 3: Load in the Data {#Ch2InClassQueT3}
### Task 4: Review Your Data. {#Ch2InClassQueT4}
### Task 5: Gathering Data with pivot_longer(). {#Ch2InClassQueT5}
### Task 6: Combining Data. {#Ch2InClassQueT6}
### Task 7: Calculating the AQ Scores.  {#Ch2InClassQueT7}
### Task 8: Practice using pipes {#Ch2InClassQueT8}

<!--chapter:end:02-s01-lab02c.Rmd-->



## Practice Your Skills
### The Ageing Brain 
### Load in the data
### Task 1 - Oldest Participant {#Ch2AssignQueT1}
### Task 2 - Arranging D-SPAN {#Ch2AssignQueT2}
### Task 3 - Foreign Language Speakers {#Ch2AssignQueT3}
### Task 4 - Creating Percentage MOCA scores {#Ch2AssignQueT4}
### Task 5 - Remove the MOCA column {#Ch2AssignQueT5}
### Task 6 - Gather the Responses together {#Ch2AssignQueT6}
### Task 7 - Joining the data {#Ch2AssignQueT7}
### Task 8 - Working the Pipes {#Ch2AssignQueT8}
### Task 9 - Difference in Musical Means {#Ch2AssignQueT9}

<!--chapter:end:02-s01-lab02d.Rmd-->



## Solutions to Questions
### Data Wrangling Basics
#### Task 1
#### Task 2
#### Task 3
#### Task 4
#### Task 5
#### Task 6
### Data Wrangling Application
#### Task 2
#### Task 3
#### Task 7 
#### Task 8
### Practice Your Skills
#### Task 1 - Oldest Participant
#### Task 2 - Arranging D-SPAN
#### Task 3 - Foreign Language Speakers
#### Task 4 - Creating Percentage MOCA scores
#### Task 5 - Remove the MOCA column
#### Task 6 - Gather the Responses together
#### Task 7 - Joining the data
#### Task 8 - Working the Pipes
#### Task 9 - Difference in Musical Means

<!--chapter:end:02-s01-lab02e.Rmd-->

# Data Visualisation Through **`ggplot2`**

## Overview

Data visualisation is very important for understanding your data. It is a key part of data analysis in exploring data, checking assumptions, and displaying results. Figures and plots allow you to get insight into patterns in your data. For example, in regards to seeing differences between groups, but also for seeing where things don't quite match up with what you think should be happening. A great example of this is Anscombe's Quartet, which you can read up about at a later date if you like - <a href = "https://en.wikipedia.org/wiki/Anscombe%27s_quartet" target = "_blank">see here</a> - four datasets given exact same means, but with very different underlying structures when visualised. The key point is that it is always good to visualise your data and visualisation should be a common step in your data skills set.

In the PsyTeachR <a href="https://psyteachr.github.io/" target = "_blank">Data Skills book</a> we introduced data visualisation using `ggplot2`, the main visualisation package of `tidyverse`. You should look back at that when working through this chapter, and you can find additional info here at the main page for the package: <a href = "https://ggplot2.tidyverse.org/" target = "_blank">ggplot2</a>.

For visualisaion we use `ggplot2` and below we have listed some great online resources that you might want to consult if you want a fuller understanding: 

* <a href="http://www.cookbook-r.com/Graphs/" target = "_blank">R Graphics Cookbook</a>
* <a href="https://ggplot2-book.org/" target = "_blank">ggplot2 book</a>
* <a href="https://www.rstudio.com/wp-content/uploads/2015/03/ggplot2-cheatsheet.pdf" target = "_blank">ggplot2 cheatsheet</a>
* <a href="http://ggplot2.tidyverse.org/reference/" target = "_blank">ggplot2 Reference Guide</a>

In this chapter, we will revisit plotting data and expand your skills in order to make effective and informative figures. This will become really beneficial to you as your progress because data visualisation is a skill that applies to multiple careers, not just Psychology.

In this chapter you will:

1. Recap on data visualisation
2. Expand your skills to produce new figures
3. Learn about Mental Rotation research

<!--chapter:end:03-s01-lab03a.Rmd-->



## Data Visualisation Basics
### Introducing the Data Set: Mental Rotation Ability
### Basic Structure of `ggplot()`
### Scatterplots - `geom_point()`
### Histograms - geom_histogram()
### Boxplots - geom_boxplot()
### Barplots - geom_bar() or geom_col()
### Themes, Labels, Guides, and **`facet_wraps()`**
### Choosing Appropriate Figures

<!--chapter:end:03-s01-lab03b.Rmd-->



## Data Visualisation Application
### Mental Rotation: Angle and Reaction Time
### Task 1: Loading and Viewing the Data {#Ch3InClassQueT1}
### Task 2: Recreating the Figure {#Ch3InClassQueT2}
### Task 3: Examining Additional Variable Effects {#Ch3InClassQueT3}
### Task 4: Grouping the Figure Data {#Ch3InClassQueT4}
### Task 5: Identifying Groups Using **`aes()`** {#Ch3InClassQueT5}
### Task 6: Changing the Shape and Size of Data Points {#Ch3InClassQueT6}
### Task 7: Adding Labels and Changing the Background {#Ch3InClassQueT7}
### Task 8: Separating a Variable and Removing Legends {#Ch3InClassQueT8}
### Final Considerations

<!--chapter:end:03-s01-lab03c.Rmd-->

## Practice Your Skills {#Ch3PracticeSkills}

In order to complete these tasks you will need to download the data .csv files and the .Rmd file, which you need to edit, titled `Ch3_PracticeSkills_Visualisations.Rmd`. These can be downloaded within a zip file from the below link. Once downloaded and unzipped, you should create a new folder that you will use as your working directory; put the data files and the .Rmd file in that folder and set your working directory to that folder through the drop-down menus at the top. [**Download the Exercises .zip file from here**](data/03-s01/Ch3_PracticeSkills_Visualisations.zip).

Now open the .Rmd file within RStudio. You will see there is a code chunk for each task. Follow the instructions on what to edit in each code chunk. This will often be entering code based on what we have covered up until this point.

Happy Data Visualising!

<!--chapter:end:03-s01-lab03d.Rmd-->



## Solutions to Questions
### Data Visualisation Application
#### Task 1
#### Task 2
#### Task 3
#### Task 4
#### Task 5
#### Task 6
#### Task 7
#### Task 8
### Practice Your Skills

<!--chapter:end:03-s01-lab03e.Rmd-->



## Additional Material
### More on `aes()`
### Combining Plots into one Figure

<!--chapter:end:03-s01-lab03f.Rmd-->


# Revisiting Probability Distributions

Placeholder


## Overview

<!--chapter:end:04-s01-lab04a.Rmd-->



## Discrete Data and Binomial Distributions
### General Probability Calculations
### Creating a Simple Probability Distribution 
### The Binomial Distribution - Creating a Discrete Distribution
### **`dbinom()`** - The Density Function
### **`pbinom()`** - The Cumulative Probability Function
### **`qbinom()`** - The Quantile Function

<!--chapter:end:04-s01-lab04b1.Rmd-->

## Continuous Data and Normal Distribution

### Continuous Data Properties

In the previous section, we have seen how we can use a distribution to estimate probabilities and determine cut-off values (these will play an important part in hypothesis testing in later chapters), but we have looked only at the **discrete binomial distribution**. Many of the variables we will encounter will be **continuous** and tend to show a **normal distribution** (e.g., height, weight, IQ).

Let's say we're interested in the height of the <a class='glossary' target='_blank' title='All members of a group that we wish to generalise our findings to. E.g. all students taking Psychology at the University of Glasgow. We draw our testing sample from the population.' href='https://psyteachr.github.io/glossary/p#population'>population</a> of psychology students, which we estimate to be between 146cm and 194cm. If we plotted this as a continuous, normal distribution, it will look like:

<div class="figure" style="text-align: center">
<img src="04-s01-lab04b2_files/figure-html/normplot1-1.png" alt="The Normal Distribution of height in Psychology students (black line). Green line represents the mean. Blue line represent 1 Standard Deviation from the mean. Yellow line represents 2 Standard Deviation from the mean. Red line represents 3 Standard Deviation from the mean." width="100%" />
<p class="caption">(\#fig:normplot1)The Normal Distribution of height in Psychology students (black line). Green line represents the mean. Blue line represent 1 Standard Deviation from the mean. Yellow line represents 2 Standard Deviation from the mean. Red line represents 3 Standard Deviation from the mean.</p>
</div>

The figure shows the probability density function of heights ranging from 146cm to 194cm in the population of Psychology students (black curve). This data is **normally distributed** and has the following properties:

<span style="font-size: 22px; font-weight: bold; color: var(--black);">Properties of the Normal distribution</span>

**1. The distribution is defined by its mean and standard deviation:** The mean   ($\mu$) describes the center, and therefore peak density, of the distribution. This is where the largest number of the people in the population will be in terms of height. The standard deviation ($\sigma$) describes how much variation there is from the mean of the distribution - on the figure, the standard deviation is the distance from the mean to the inflection point of the curve (the part where the curve changes from a upside-down bowl shape to a right-side-up bowl shape).  

**2. Distribution is symmetrical around the mean:** The mean lies in the middle of the distribution and divides the area under the curve into two equal sections - so we get the typical bell-shaped curve.  

**3. Total area under the curve is equal to 1:** The probability of a value falling between two limits is equal to the area under the curve between those two limits. Since probability is bound between 0 and 1, and a value must fall between -$\infty$ and +$\infty$, the total area under the curve between the limits of -$\infty$ and +$\infty$ is 1. 

**4. The mean, median and mode are all equal:** A good way to check if a given dataset is normally distributed is to calculate each measure of central tendency and see if they are approximately the same (normal distribution) or not (skewed distribution).  

**5. The curve approaches, but never touches, the x axis:** You will never have a probability of 0 for a given x axis value. 

**6. The normal distribution follows the Empirical Rule:** The Empirical Rule states that 99.7% of the data within the normal distribution falls within three standard deviations ($\pm3\sigma$) from the mean, 95% falls within two standard deviations ($\pm2\sigma$), and 68% falls within one standard deviation ($\pm\sigma$).


Continuous data can take any precise and specific value on a scale, e.g. 1.1, 1.2, 1.11, 1.111, 1.11111. Many of the variables we will encounter in Psychology will:  

* be **continuous** as opposed to discrete. 
* tend to show a **normal distribution**. 
* look similar to below - the bell-shaped curve - when plotted.


### Estimating from the Normal Distribution

Unlike coin flips, the outcome in the normal distribution is not just 50/50 and as such we won't ask you to create a normal distribution as it is more complicated than the binomial distribution you estimated in the previous section. Instead, just as with the binomial distribution (and other distributions) there are functions that allow us to estimate the normal distribution and to ask questions about the distribution. These are:

* `dnorm()` - the Density function for the normal distribution
* `pnorm()` - the Cumulative Probability function for the normal distribution
* `qnorm()` - the Quantile function for the normal distribution

You might be thinking those look familiar. They do in fact work in a similar way to their binomial counterparts. If you are unsure about how a function works remember you can call the help on it by typing in the console, for example, `?dnorm` or `?dnorm()`.
<br>

<span style="font-size: 22px; font-weight: bold; color: var(--green);">Quickfire Questions</span>

* Type in the box the binomial counterpart to `dnorm()`? <input class='webex-solveme nospaces' size='10' data-answer='["dbinom()"]'/>

* Type in the box the binomial counterpart to `pnorm()`? <input class='webex-solveme nospaces' size='10' data-answer='["pbinom()"]'/>

* Type in the box the binomial counterpart to `qnorm()`? <input class='webex-solveme nospaces' size='10' data-answer='["qbinom()"]'/>


<div class='webex-solution'><button>Explain This - I don't get the answers</button>

<div class="info">
<p>The counterpart functions all start with the same letter, d, p, q, it
is just the distribution name that changes, <code>binom</code>,
<code>norm</code>, <code>t</code> - though we haven't quite come across
the t-distribution yet.</p>
<ol style="list-style-type: decimal">
<li><p><code>dbinom()</code> is the binomial equivalent to
<code>dnorm()</code></p></li>
<li><p><code>pbinom()</code> is the binomial equivalent to
<code>pnorm()</code></p></li>
<li><p><code>qbinom()</code> is the binomial equivalent to
<code>qnorm()</code></p></li>
</ol>
<p>There is also <code>rnorm()</code> and <code>rbinom()</code> but we
will look at them another time.</p>
</div>

</div>


### **`dnorm()`** - The Density Function

Using `dnorm()`, like we did with `dbinom`, we can plot a normal distribution. This time however we need: 

* `x`, a vector of quantiles (in other words, a series of values for the x-axis - think of this as the max and min of the distribution we want to plot) 
* the `mean` of our data
* and standard deviation `sd` of our data. 

We will use IQ as an example. There is actually some disagreement of whether or not IQ is continuous data and to some degree it will depend on the measurement you use. IQ however is definitely normally distributed and we will assume it is continuous for the purposes of this demonstration. Many Psychologists are interested in studying IQ, perhaps in terms of heritability, or interested in controlling for IQ in their own studies to rule out any effect (e.g., clinical and autism studies).  

#### Task 1: Standard Deviations and IQ Score Distribution {#Ch4InClassQueT1}

1. Copy the below code into a new script and run it. Remember that you will need to call `tidyverse` to your library first. 

This code creates the below plot showing a normal distribution of IQ scores (M = 100, SD = 15) ranging from 40 to 160. These are values considered typical for the general population.

* First we set up our range of IQ values from 40 to 160
* Then we plot the distribution of IQ_data, where we have M = 100 and SD = 15


```r
IQ_data <- tibble(IQ_range = c(40, 160))

ggplot(IQ_data, aes(IQ_range)) + 
  stat_function(fun = dnorm, args = list(mean = 100, sd = 15)) +
  labs(x = "IQ Score", y = "Likelihood") +
  theme_classic()
```

<div class="figure" style="text-align: center">
<img src="04-s01-lab04b2_files/figure-html/normplot-1.png" alt="Distribution of IQ scores with mean = 100, sd = 15" width="100%" />
<p class="caption">(\#fig:normplot)Distribution of IQ scores with mean = 100, sd = 15</p>
</div>

* Which part of the code do you need to change to alter the SD of your plot? <select class='webex-select'><option value='blank'></option><option value=''>mean = 100</option><option value='answer'>sd = 15</option><option value=''>(40, 160)</option></select>

2. Now copy and edit the above code to plot a distribution with `mean = 100` and `sd = 10`, and visually compare the two plots. 
<br>

<span style="font-size: 22px; font-weight: bold; color: var(--pink);">Thinking Cap Point</span>

What does changing the standard deviation (`sd`) do to the shape of the distribution? Spend a few minutes changing the code to various values and running it, and discussing with your group to answer the following questions:

* What happens to the shape of the distribution if you change the `sd` from 10 to 20? <select class='webex-select'><option value='blank'></option><option value=''>the distribution gets narrower</option><option value='answer'>the distribution gets wider</option></select>

* What happens to the shape of the distribution if you change the `sd` from 10 to 5? <select class='webex-select'><option value='blank'></option><option value='answer'>the distribution gets narrower</option><option value=''>the distribution gets wider</option></select>

* What does a small or large standard deviation in your sample tell you about the data you have collected?


<div class='webex-solution'><button>Explain This - I don't get Standard Deviations!</button>

<div class="info">
<ol style="list-style-type: decimal">
<li>Changing the SD from 10 to 20 means a larger standard deviation so
you will have a wider distribution.</li>
<li>Changing the SD from 10 to 5 means a smaller standard deviation so
you will have a narrower distribution.</li>
<li>Smaller SD results in a narrower distribution meaning that the data
is less spread out; larger SD results in a wider distribution meaning
the data is more spread out.</li>
</ol>
<p><strong>A note on the Standard Deviation</strong>:</p>
<p>You will know from your lectures that you can estimate data in two
ways: point-estimates and spread estimates. The mean is a point-estimate
and condenses all your data down into one data point - it tells you the
average value of all your data but tells you nothing about how spread
out the data is. The standard deviation however is a spread estimate and
gives you an estimate of how spread out your data is from the mean - it
is a measure of the standard deviation from the mean.</p>
<p>So imagine we are looking at IQ scores and you test 100 people and
get a mean of 100 and an SD of 5. This means that the vast majority of
your sample will have an IQ around 100 - probably most will fall within
1 SD of the mean, meaning that most of your participants will have an IQ
of between 95 and 105.</p>
<p>Now if you test again and find a mean of 100 and an SD of 20, this
means your data is much more spread out. If you take the 1 SD approach
again then most of your participants will have an IQ of between 80 and
120.</p>
<p>So one sample has a very tight range of IQs and the other sample has
a very wide range of IQs. All in, from the point-estimate and spread
estimate of your data you can tell the shape of your sample
distribution.</p>
</div>

</div>

<br>
So far so good! But in the above example we told `dnorm()` the values at the limit of our range and it did the rest; we said give us a range of 40 to 160 IQ scores. However, we could plot it another way by telling `dnorm()` the sequence, or range, of values we want and how much precision we want between them.  

#### Task 2: Changing Range and Step Size of The Normal Distribution {#Ch4InClassQueT2}

1. Copy the code below in to your script and run it. 
Here we plot the standard Normal Distribution from -4 to 4 in steps of 0.01. We have also stated a mean of 0 and an sd of 1.


```r
ND_data <- tibble(ND_range = seq(-4, 4, 0.01))
ggplot(ND_data, aes(ND_range)) + 
  stat_function(fun = dnorm, args = list(mean = 0, sd = 1)) +
  labs(x = "SD units", y = "Likelihood", title = "The Normal Distribution") +
  theme_classic()
```

<div class="figure" style="text-align: center">
<img src="04-s01-lab04b2_files/figure-html/ND-example-1.png" alt="The Normal Distribution with Mean = 0 and SD = 1" width="100%" />
<p class="caption">(\#fig:ND-example)The Normal Distribution with Mean = 0 and SD = 1</p>
</div>
<br>
<span style="font-size: 22px; font-weight: bold; color: var(--green);">Quickfire Questions</span>

* Fill in the box to show what you would type to create a tibble containing a column called `ND_range` that has values ranging from `-10` to `10` in steps of `.05`:

**ND_data** <- <input class='webex-solveme nospaces' size='40' data-answer='["tibble(ND_range = seq(-10, 10, 0.05))","tibble(ND_range = seq(-10, 10, .05))"]'/>

Now that you know what to change, try plotting a normal distribution with the following attributes:

* range of -10 to 10 in steps of 0.05, 
* a mean of 0, 
* and a standard deviation of 1.

* Compare your new plot the the original one we created. What change is there in the distribution? <select class='webex-select'><option value='blank'></option><option value=''>Distribution widens</option><option value='answer'>No change in distribution</option><option value=''>Distribution narrows</option></select>


<div class='webex-solution'><button>Explain This - I don't understand the answer!</button>

<div class="info">
<p>To change the distribution you would write:
<code>ND_data &lt;- tibble(ND_range = seq(-10, 10, 0.05))</code></p>
<p>However, when comparing the plots, whilst the plot itself may look
thinner, the distribution has not changed. The change in appearance is
due to the range of <code>sd</code> values which have been extended from
-4 and 4 to -10 and 10. The density of values within those values has
not changed however and you will see, more clearly in the second plot,
that values beyond -3 and 3 are very unlikely.</p>
</div>

</div>


Remember, every value has a likelihood on a distribution and we have been able to use the `dnorm()` function to get a visual representation of how the likelihood of values change in the normal distribution. Some values are very likely. Some values are less likely. This is a key concept when it comes to thinking about significant differences later. 

However, as you know, there is one important difference between continuous and discrete probability distributions - the number of possible outcomes. With discrete probability distributions there are usually a finite number of outcomes over which you take a probability. For instance, with 5 coin flips, there are 5 possible outcomes for the number of heads: 0, 1, 2, 3, 4, 5. And because the binomial distribution has exact and finite outcomes, we can use `dbinom()` to get the exact probability for each outcome. 

In contrast, with a truly continuous variable, the number of possible outcomes are infinite, because you not only have 0.01 but also .0000001 and .00000000001 to arbitrary levels of precision. So rather than asking for the probability of a variable taking a single value, we ask the probability for a variable to fall within a **range of values**, which is equal to the area under the curve (the black line in the plots above) for that range of values.

As such, we will leave `dnorm()` for now and move onto looking at establishing the probability of a range of values using the Cumulative Probability function

### **`pnorm()`** - The Cumulative Distribution Function

Just as `dnorm()` works like `dbinom()`, `pnorm()` works just like `pbinom()`. So, `pnorm()`, given the `mean` and `sd` of our data, returns the **cumulative distribution function**, which shows the probability that a variable lies **on or below a specified cut-off value**. If `lower.tail = FALSE` is specified, it shows the probability that a variable lies **on or above that cut-off value **. 

OK, in English that people can understand, that means the `pnorm()` function tells you the probability of obtaining a given value or lower if you set `lower.tail = TRUE`.  Contrastingly, `pnorm()` function tells you the probability of obtaining a given value or higher if you set `lower.tail = FALSE`.

We will use height to give a concrete example. Say that we test a sample of students (M = 170cm, SD = 7) and we we want to calculate the probability that a given student is 150cm or shorter we would do the following:

* Remember, `lower.tail = TRUE` means lower than and including the value of X
* `TRUE` is the default so we don't actually need to declare it


```r
pnorm(150, 170, 7, lower.tail = TRUE)
```

This tells us that finding the probability of someone 150cm or shorter in our class is about **p = 0.0021374**. Stated differently, we would expect the proportion of students to be 150cm or shorter to be **0.21%** (You can convert probability to proportion by multiplying the probability by 100). This is a very small probability and suggests that it is pretty unlikely to find someone shorter than 150cm in our class. This is mainly because of how small the standard deviation of our distribution is. Think back to what we said earlier about narrow standard deviations round the mean! 

Another example might be, what would be the probability of a given student being 195 cm or taller? To do that, you would set the following code:


```r
pnorm(195, 170, 7, lower.tail = FALSE)
```

This tells us that finding the probability of someone 195cm or taller in our class is **0.02%**. So again, really unlikely.

Did you notice something different about the cut-off for this example and from when using the `dbinom()` function and looking above a cut-off? Why might that be? We will discuss in a second but first a quick task.

#### Task 3: Calculating Cumulative Probability of Height {#Ch4InClassQueT3}

1. Edit the `pnorm()` code above to calculate the probability that a given student is 190cm **or taller**.

To three decimal places, as in Task 3, what is the probability of a student being 190cm or taller in this class? <input class='webex-solveme nospaces' size='5' data-answer='["0.002",".002"]'/>


<div class='webex-solution'><button>Explain This - I don't understand the answer or the tail!</button>

<div class="info">
<p>The answer is .002. See the solution code at the end of the
chapter.</p>
<p>The key thing is that there is a difference in where you need to
specify the cut-off point in the <code>pbinom()</code> (discussed in the
preclass activity) and <code>pnorm()</code> functions for values
<strong>above</strong> <code>x</code>, i.e. when
<strong><code>lower.tail = FALSE</code></strong>.</p>
<p>If you had discrete data, say the number of coin flips that result in
<code>heads</code>, and wanted to calculate the probability above
<code>x</code>, you would apply <code>pbinom()</code> and have to
specify your cut-off point as <strong><code>x-1</code></strong> to
include <code>x</code> in your calculation. For example, to calculate
the probability of 4 or more 'heads' occuring in 10 coin flips, you
would specify <code>pbinom(3, 10, 0.5, lower.tail = FALSE)</code> as
<code>lower.tail</code> includes the value you state.</p>
<p>For continuous data, however, such as height, you would be applying
<code>pnorm()</code> and therefore can specify your cut-off point simply
as <strong><code>x</code></strong>. In the above example, for the
cut-off point of 190, a mean of 170 and standard deviation of 7, you can
write <code>pnorm(190, 170, 7, lower.tail = FALSE)</code>. The way to
think about this is that setting <code>x</code> as 189 on a continuous
scale, when you only want all values greater than 190, would also
include all the possible values between 189 and 190. Setting
<code>x</code> at 190 starts it at 190.0000000...001.</p>
<p>This is a tricky difference between <code>pbinom()</code> and
<code>pnorm()</code> to recall easily, so best include this explanation
point in your portfolio to help you carry out the correct analyses in
the future!</p>
</div>

</div>
  

#### Task 4: Using Figures to Calculate Cumulative Probability {#Ch4InClassQueT4}

Have a look at the probability density function below:

<div class="figure" style="text-align: center">
<img src="04-s01-lab04b2_files/figure-html/pnormplot1-1.png" alt="The Normal Distribution of Height with the probability of people of 185cm highlighted in purple, with a mean = 170cm and SD = 7" width="100%" />
<p class="caption">(\#fig:pnormplot1)The Normal Distribution of Height with the probability of people of 185cm highlighted in purple, with a mean = 170cm and SD = 7</p>
</div>

1. Using the information in the figure, and the mean and SD as above, calculate the probability associated with the shaded area.


<div class='webex-solution'><button>Helpful Hint</button>

<div class="info">
<p>You already have your mean and standard deviations to input in
<code>pnorm()</code>, look at the shaded area to obtain your cut-off
point. What should the <code>lower.tail</code> call be set to according
to the shaded area?</p>
</div>

</div>

<br>
<span style="font-size: 22px; font-weight: bold; color: var(--green);">Quickfire Question</span>

To three decimal places, what is the cumulative probability indicated by the shaded area in Task 4?  <input class='webex-solveme nospaces' size='5' data-answer='["0.016",".016"]'/>


<div class='webex-solution'><button>Explain This - I don't get this answer</button>

<div class="info">
<p>The answer should be p = .016. See the solution code at the end of
the chapter for the correct code.</p>
<p>Remember, <code>lower.tail</code> is set to FALSE as you want the
area to the right.</p>
</div>

</div>
  

So `pnorm()` is great for telling us the probability of obtaining a specific value or greater on a distribution, given the mean and standard deviation of the distribution. The significance of this will come clearer in the coming chapters but this is a key point to have in mind as we progress through our understanding of analyses. We will leave it there for now and look at the last function of the normal distribution.


### **`qnorm()`** - The Quantile Function

Using `qnorm()` we can do the inverse of `pnorm()`, and instead of finding out the cumulative probability from a given set of values (or to a cut-off value), we can find a cut-off value given a desired probability. For example, we can use the `qnorm()` function to ask what is the maximum IQ a person would have if they were in the bottom 10% of the above IQ distribution (`M = 100` & `SD = 15`)?

* **Note:** We first need to convert 10% to a probability by dividing by 100 
* 10% = 10 / 100 = 0.1.


```r
qnorm(0.1, 100, 15) 
```

So anyone with an IQ of **80.8** or lower would be in the bottom 10% of the distribution. Or to rephrase that, a person in the bottom 10% of the distribution would have a max IQ value of **80.8**. 

To recap, we have calculated the **inverse cumulative density function (or inverse of the cumulative probability)** of the **lower tail** of the distribution, with a cut-off of a probability of 0.1 (10%), illustrated in purple below:

<div class="figure" style="text-align: center">
<img src="04-s01-lab04b2_files/figure-html/pnormplot2-1.png" alt="The Normal Distribution of Height with the bottom 10% of heights highlighted in purple" width="100%" />
<p class="caption">(\#fig:pnormplot2)The Normal Distribution of Height with the bottom 10% of heights highlighted in purple</p>
</div>

Again, in English that people can understand, that means the `qnorm()` function tells you the maximum value a person can have to maintain a given probability if you set `lower.tail = TRUE`.  Alternatively, the `pnorm()` function tells you the the minimum value a person can have to maintain a given probability if you set `lower.tail = FALSE`.

#### Task 5: Using **`pnorm()`** and **`qnorm()`** to find probability and cut-off values {#Ch4InClassQueT5}

1. Calculate the lowest IQ score a student must have to be in the top 5% of the above distribution.  

2. More challenging: Using the appropriate normal distribution function, calculate the probability that a given student will have an IQ between 105 and 110 given a normal distribution of mean = 100, sd = 15.  


<div class='webex-solution'><button>Helpful Hint</button>

<div class="info">
<p>Part 1: Remember to include the <code>lower.tail</code> call if
required! If you are unsure, visualise what you are trying to find (i.e.
the lowest IQ score you can have to be in top 5%) by sketching it out on
a normal distribution curve. It may help to reverse the question to
sound more like the previous example.</p>
<p>Part 2: For the second part, each function, not necessarily
<code>qnorm()</code>, gives one value, so you are looking to do a
separate calculation for each IQ. Then you have to combine these two
values, but are you summing or subtracting them? Is it more or less
likely for students to have an IQ that falls between this range than
above or below a cut-off? Again try sketching out what you are trying to
achieve.</p>
</div>

</div>

<br>
<span style="font-size: 22px; font-weight: bold; color: var(--green);">Quickfire Questions</span>

* To one decimal place, enter your answer for Task 5 part 1: What is the lowest IQ score a student must have to be in the top 5% of the distribution? <input class='webex-solveme nospaces' size='5' data-answer='["124.7"]'/>

* To two decimal places, enter your answer for Task 5 part 2: What is the probability that a student will have an IQ between 105 and 110, on a normal distribution of mean = 100, sd = 15? <input class='webex-solveme nospaces' size='4' data-answer='["0.12",".12"]'/>
<br>

<div class='webex-solution'><button>Explain This - I dont get this answer</button>

<div class="info">
<ol style="list-style-type: decimal">
<li><p>The question can be rephrased as what value would give you 95% of
the distribution - and the answer would be 124.7. See the solution code
for Task 5 Question 1 at the end of the chapter.</p></li>
<li><p>You could use <code>pnorm()</code> to establish the probability
of an IQ of 110. And you could use <code>pnorm()</code> again to
establish the probability of an IQ of 105. The answer is the difference
between these two probabilities and should be p = .12. See the solution
code for Task 5 Question 2 at the end of the chapter.</p></li>
</ol>
</div>

</div>


<!--chapter:end:04-s01-lab04b2.Rmd-->



## Practice Your Skills
### Topic: Probabilities
### Load in the Library {#Ch4AssignQueLib}
### Task 1 {#Ch4AssignQueT1}
### Task 2 {#Ch4AssignQueT2}
### Task 3 {#Ch4AssignQueT3}
### Task 4 {#Ch4AssignQueT4}
### Task 5 {#Ch4AssignQueT5}
### Task 6 {#Ch4AssignQueT6}
### Task 7 {#Ch4AssignQueT7}
### Task 8 {#Ch4AssignQueT8}
### Task 9 {#Ch4AssignQueT9}
### Task 10 {#Ch4AssignQueT10}

<!--chapter:end:04-s01-lab04d.Rmd-->



## Solutions to Questions
### Continuous Data and Normal Distribution Tasks
#### Task 1
#### Task 2
#### Task 3
#### Task 4
#### Task 5
### Practice Your Skills
#### Load in the Library
#### Task 1
#### Task 2
#### Task 3
#### Task 4
#### Task 5
#### Task 6
#### Task 7
#### Task 8
#### Task 9
#### Task 10

<!--chapter:end:04-s01-lab04e.Rmd-->


# NHST: Binomial test and One-Sample t-test

Placeholder


## Overview
## Brief Introduction to NHST

<!--chapter:end:05-s01-lab06a.Rmd-->



## Background of data: Sleep

<!--chapter:end:05-s01-lab06b1.Rmd-->



## The Binomial Test
### Task 1: Creating a Dataframe {#Ch6PreClassQueT1}
### Task 2: Comparing Original and New Sample Reaction Times {#Ch6PreClassQueT2}
### Task 3: Calculating Probability {#Ch6PreClassQueT3}

<!--chapter:end:05-s01-lab06b2.Rmd-->



## The One-Sample t-test
### Task 4: Calculating the Mean and Standard Deviation {#Ch6PreClassQueT4}
### Task 5: Calculating the Observed Test Statistic {#Ch6PreClassQueT5}
### Task 6: Comparing the Observed Test Statistic to the t-distribution using **`pt()`** {#Ch6PreClassQueT6}
### Task 7: Comparing the Observed Test Statistic to the t-distribution using **`t.test()`** {#Ch6PreClassQueT7}
### Task 8: Drawing Conclusions about the new data {#Ch6PreClassQueT8}

<!--chapter:end:05-s01-lab06b3.Rmd-->



## Practice Your Skills
### Does Music Convey Social Information to Infants? 
### Load in the data {#Ch5PracticeSkillsT0}
### Task 1 - Filter data {#Ch5PracticeSkillsT1}
### Task 2 - Select data {#Ch5PracticeSkillsT2}
### Task 3 - Testing baseline gazing proportion {#Ch5PracticeSkillsT3}
### Task 4 - Testing test trial gazing proportion {#Ch5PracticeSkillsT4}
### Task 5 - Gathering data into a different format {#Ch5PracticeSkillsT5}
### Task 6 - Visualise baseline and test trial data {#Ch5PracticeSkillsT6}
### Task 7 - Compare your analyses with the analyses reported in the published paper {#Ch5PracticeSkillsT7}

<!--chapter:end:05-s01-lab06c.Rmd-->



## Solutions to Questions
### The Binomial Test
#### Task 1
#### Task 2
#### Task 3
### The One-Sample t-test
#### Task 4
#### Task 5
#### Task 6
#### Task 7
#### Task 8
### Practice Your Skills
#### Load in the data
#### Task 1 - Filter data
#### Task 2 - Select data
#### Task 3 - Testing baseline gazing proportion
#### Task 4 - Testing test trial gazing proportion
#### Task 5 - Gathering data into a different format
#### Task 6 - Visualise baseline and test trial data
#### Task 7 - Compare your analyses with the analyses reported in the published paper

<!--chapter:end:05-s01-lab06d.Rmd-->


# NHST: Two-Sample t-test

Placeholder


## Overview
## Background of data: Speech as indicator of intellect
## The Two-Sample t-test
### Task 1: Evaluators {#Ch6InClassQueT1}
### Task 2: Ratings {#Ch6InClassQueT2}
### Task 3: Creating a Figure {#Ch6InClassQueT3}
### Task 4: t-tests {#Ch6InClassQueT4}

<!--chapter:end:06-s01-lab06a.Rmd-->



## Student's versus Welch's t-tests

<!--chapter:end:06-s01-lab06b.Rmd-->



## Practice Your Skills
### Single-dose testosterone administration impairs cognitive reflection in men.
### Task 1A: Libraries {#Ch6AssignQueT1A}
### Task 1B: Loading in the data {#Ch6AssignQueT1B}
### Task 2: Selecting only relevant columns {#Ch6AssignQueT2}
### Task 3: Verify the number of subjects in each group {#Ch6AssignQueT3}
### Task 4: Reproduce Figure 2a {#Ch6AssignQueT4}
### Task 5: Interpreting your Figure {#Ch6AssignQueT5}
### Task 6: t-test {#Ch6AssignQueT6}
### Task 7: Reporting results {#Ch6AssignQueT7}

<!--chapter:end:06-s01-lab06c.Rmd-->



## Solutions to Questions
### The Two-Sample t-test
#### Task 1
#### Task 2
#### Task 4
### Practice Your Skills
#### Task 1A: Libraries
#### Task 1B: Loading in the data
#### Task 2: Selecting only relevant columns
#### Task 3: Verify the number of subjects in each group
#### Task 4: Reproduce Figure 2A
#### Task 5: Interpreting your Figure
#### Task 6: t-test
#### Task 7: Reporting results

<!--chapter:end:06-s01-lab06d.Rmd-->


# NHST: Paired-Sample t-test and Nonparametric tests

Placeholder


## Overview

<!--chapter:end:07-s01-lab07a.Rmd-->



## The Paired-Sample t-test
### Data Set: Juror Decision Making
### Task 1: Load the data {#Ch7InClassQueT1}
### Task 2: Wrangle the data {#Ch7InClassQueT2}
### Task 3: Look at the histogram for normality {#Ch7InClassQueT3}
### Task 4: A boxplot of outliers {#Ch7InClassQueT4}
### Task 5: The violin plot {#Ch7InClassQueT5}
### Task 6: Calculating Descriptives {#Ch7InClassQueT6}
### Task 7: Visualising Means and Descriptives {#Ch7InClassQueT7}
### Task 8: The paired-sample t-test {#Ch7InClassQueT8}
### Task 9: The Write-up {#Ch7InClassQueT9}

<!--chapter:end:07-s01-lab07b.Rmd-->

## Practice Your Skills

Using the data from above, perform a paired-sample t-test for the **Middle** group where the crucial evidence was presented on Timepoint 9. Save your current .Rmd file, then make a copy of it, rename it accordingly, and go through the steps for the **Middle** group. Since this exercise is very close to the example we worked through in this chapter, we have not added the solutions in the end. Feel free to check with your peers and discuss if there is **a difference in ratings of guilt, caused by presentation of the critical evidence, from Timepoint 8 to Timepoint 9**?

<!--chapter:end:07-s01-lab07c.Rmd-->



## Non-Parametric tests
### Our Scenario
### Assumption check
### The descriptives
### Running the inferential test
### Last point on calculating U and reporting the test

<!--chapter:end:07-s01-lab07d.Rmd-->



## Solutions to Questions
### The Paired-Sample t-test
#### Task 1
#### Task 2
#### Task 3
#### Task 4
#### Task 5
#### Task 6
#### Task 7
#### Task 8
#### Task 9

<!--chapter:end:07-s01-lab07e.Rmd-->

# APES - Alpha, Power, Effect Sizes, Sample Size

## Overview

Up until now we have mainly spent time on data-wrangling, understanding probability, visualising our data, and more recently, running inferential tests, i.e. t-tests. In the lectures, however, you have also started to learn about additional aspects of inferential testing and trying to reduce certain types of error in your analyses. It is this balance of minimising error in our inferential statisitcs that we will focus on in this chapter. 

First thing to remember is that there are two types of hypotheses in Null Hypothesis Significance Testing (NHST) and what you are trying to establish is the probability of the null hypothesis not being accepted. Those two hypotheses are:

* The **null hypothesis** which states that the compared values **are equivalent** and, when referring to means, is written as: $H_0: \mu_1 = \mu_2$ 
* And the **alternative hypothesis** which states that the compared values **are not equivalent** and, when referring to means, is written as: $H_1: \mu_1 \ne \mu_2$.

Now, each decision about a hypothesis is prone to some degree of error and, as you will learn, the two main types of error that we worry about in Psychology are:

* **Type I error** - or **False Positives**, is the error of rejecting the null hypothesis when it should not be rejected (otherwise called **alpha** or $\alpha$). In other words, you conclude that there is a real "effect" when in fact there is no effect. The field standard rate of acceptable false positives is $\alpha = .05$ meaning that in theory 1 in 20 studies may be a false positive.
* **Type II error** - or **False Negatives**, is the error of retaining the null hypothesis when it is false (otherwise called **beta** or $\beta$). In other words, you conclude that there was no real "effect" when in fact there was one. The field standard rate of acceptable false negatives is $\beta = .2$ meaning that in theory 1 in 5 studies may be a false negative. 

Adding to the ideas of hypotheses and errors, we are going to look at the idea of **power** which you will learn is the long-run probability of correctly rejecting the null hypothesis for a fixed effect size and fixed sample size; i.e. correctly concluding there is an effect when there is a real effect to detect. Power is calculated as $power = 1-\beta$ and is directly related to the False Negative rate. If the field standard of False Negatives is $\beta = .2$ then the field standard of power should be $power = 1 - .2 = .8$, for a given effect size and sample size (though some papers, including Registered Reports are often required to have a power of at least $power >= .9$). As such, $power = .8$ means that the majority of studies should find an effect if there is one to detect, assuming that your study maintains these rates of error and power.

Unfortunately, however, psychological research has been criticised for neglecting power and $\beta$ when planning studies resulting in what are called "underpowered" or "low powered" studies - meaning that your error rates are higher than you think they are, your power is lower than you think it is, and the study is unreliable. Note that as $\beta$ increases (the false negative rate increases), power decreases; power and false positive rates are also related, though less directly. In fact, low powered studies, combined with undisclosed analytical flexibility and publication bias, is thought to be a key issue in the replication crisis within the field. As such there may be a large number of studies where the null hypothesis has been rejected when it should not have been, and unpublished studies that have not been written up because they did not find an effect when they should have. In turn, when that is the case, the field becomes noisy and you are unsure which studies will replicate.  It is issues like this that led us to redevelop our courses and why we really want you to understand power as much as possible.

So this chapter is all about power, error rates, effect sizes, and sample sizes. We will learn:

* the relationship between power, alpha, effect sizes and sample sizes
* how to calculate certain effect sizes
* how to determine appropriate sample sizes in given scenarios
* and how to interpret power analyses.


<!--chapter:end:08-s01-lab08a.Rmd-->



## Introduction to Power
### Blog post 
### Video about power and sample size
### Useful links

<!--chapter:end:08-s01-lab08b.Rmd-->



## Practical APES Calculations
### Task 1: Effect size from a one-sample t-test {#Ch8InClassQueT1}
### Task 2: Effect size from a two-sample t-test {#Ch8InClassQueT2}
### Task 3: Effect Size from a matched-sample t-test {#Ch8InClassQueT3}
### Task 4: t-value and effect size for a between-subjects experiment {#Ch8InClassQueT4}
### Task 5: Sample size for standard power one-sample t-test {#Ch8InClassQueT5}
### Task 6: Effect size from a high power between-subjects t-test {#Ch8InClassQueT6}
### Task 7: Power of Published Research {#Ch8InClassQueT7}

<!--chapter:end:08-s01-lab08c.Rmd-->



## Practice Your Skills
### Task 1 {#Ch8AssignQueT1}
### Task 2 {#Ch8AssignQueT2}
### Task 3 {#Ch8AssignQueT3}
### Task 4 {#Ch8AssignQueT4}
### Task 5 {#Ch8AssignQueT5}
### Task 6 {#Ch8AssignQueT6}
### Task 7 {#Ch8AssignQueT7}
### Task 8 {#Ch8AssignQueT8}
### Task 9 {#Ch8AssignQueT9}
### Task 10 {#Ch8AssignQueT10}
### Task 11 {#Ch8AssignQueT11}
### The **`pwr`** package

<!--chapter:end:08-s01-lab08d.Rmd-->



## Solutions to Questions
### Practical APES Calculations
#### Task 1
#### Task 2
#### Task 3
#### Task 4
#### Task 5
#### Task 6
#### Task 7
### Practice Your Skills
#### Task 1
#### Task 2
#### Task 3
#### Task 4
#### Task 5 
#### Task 6
#### Task 7
#### Task 8
#### Task 9
#### Task 10
#### Task 11

<!--chapter:end:08-s01-lab08e.Rmd-->


# Correlations

Placeholder


## Overview

<!--chapter:end:09-s02-lab09a.Rmd-->



## Correlations Basics
### Read
### Watch
### Play

<!--chapter:end:09-s02-lab09b.Rmd-->



## Correlations Application
### Task 1 - The Data {#Ch10InClassQueT1}
### Task 2 - Interval or Ordinal {#Ch10InClassQueT2}
### Task 3 - Missing Data {#Ch10InClassQueT3}
### Task 4 - Normality {#Ch10InClassQueT4}
### Task 5 - Descriptives {#Ch10InClassQueT5}
### Task 6 - Pearson or Spearman? {#Ch10InClassQueT6}
### Task 7 - Interpretation {#Ch10InClassQueT7}
### Task 8 - The Matrix {#Ch10InClassQueT8}
### Task 9 - Attitudes to Vaping {#Ch10InClassQueT9}

<!--chapter:end:09-s02-lab09c.Rmd-->

## Practice Your Skills {#Ch9PracticeSkills}

The purpose of this exercise is to test your ability to run and interpret a correlation for yourself, as shown in this chapter, but at the same time get you to think about all the skills you learnt previously. Most of the hard work is in the data wrangling; running the actual analysis, much like with t-tests, is very straightforward. Remember to refer back to previous chapters when stuck.


In order to complete these tasks you will need to download the data .csv file and the .Rmd file, which you need to edit, titled `GUID_L2_Ch9_PracticeSkills.Rmd`. These can be downloaded within a zip file from the below link. [**Download the Exercises .zip file from here**](data/09-s02/GUID_L2_Ch9_PracticeSkills/L2_Ch9_PracticeSkills.zip).

In that zip file, you will also find the activity html file where you can check the table and figure to be reproduced for tasks 8 and 9.

Once downloaded and unzipped you should create a new folder that you will use as your working directory; put the data file and the .Rmd file in that folder and set your working directory to that folder through the drop-down menus at the top. The .Rmd file itself will currently knit as there are no errors in the code and this is a good test that you can perform from time to time to make sure that there are still no errors in your code. Obviously this doesn't mean that all your answers are correct; it just means that the code is error free.

As in the previous exercises there are a number of code chunks already set up. The code chunks will require entering a number or entering and adjusting code that you have practiced in the chapters. Follow the instructions on what to edit in each code chunk. This will often be entering code based on what we have covered up until this point.

**Background**
The backdrop for the exercise is the following study:

Dawtry, R. J., Sutton, R. M., & Sibley, C. G. (2015). *Why wealthier people think people are wealthier, and why it matters: From social sampling to attitudes to redistribution. Psychological Science, 26, 1389-1400.* <a href = "http://journals.sagepub.com/stoken/default+domain/RrNc7nRzBpvJaMH5UEte/full" target = "_blank">Available on through this link with your VPN switched on</a>

The abstract of Dawtry, Sutton and Sibley (2015) reads:

**The present studies provide evidence that social-sampling processes lead wealthier people to oppose redistribution policies. In samples of American Internet users, wealthier participants reported higher levels of wealth in their social circles (Studies 1a and 1b). This was associated, in turn, with estimates of higher mean wealth in the wider U.S. population, greater perceived fairness of the economic status quo, and opposition to redistribution policies. Furthermore, mods from a large-scale, nationally representative New Zealand survey revealed that low levels of neighborhood-level socioeconomic deprivation - an objective index of wealth within participants' social circles - mediated the relation between income and satisfaction with the economic status quo (Study 2). These findings held controlling for relevant variables, including political orientation and perceived self-interest. Social-structural inequalities appear to combine with social-sampling processes to shape the different political attitudes of wealthier and poorer people.**

And is summarised by the <a href="https://sites.google.com/view/openstatslab/home/correlation-activities?authuser=0" target = "_blank">Open Stats Lab</a> as

**In this research, Dawtry, Sutton, and Sibley (2015) wanted to examine why people differ in their assessments of the increasing wealth inequality within developed nations. Previous research reveals that most people desire a society in which the overall level of wealth is high and that wealth is spread somewhat equally across society. However, support for this approach to income distribution changes across the social strata. In particular, wealthy people tend to view society as already wealthy and thus are satisfied with the status quo, and less likely to support redistribution. In their paper Dawtry et al., (2015) sought to examine why this is the case. The authors propose that one reason wealthy people tend to view the current system is fair is because their social-circle is comprised of other wealthy people, which biases their perceptions of wealth, which leads them to overestimate the mean level of wealth across society.**

**To test this hypothesis, the authors conducted a study with 305 participants, recruited from an online participant pool. Participants reported their own annual household income, the income level of those within their own social circle, and the income for the entire population. Participants also rated their perception of the level of equality/inequality across their social circle and across society, their level of satisfaction with and perceived fairness of the current system (measured using two scales), their attitudes toward redistribution of wealth (measured using a four-item scale), and their political preference.**

The Open Stats Lab has an activity for this paper already set up that you can work through later for your own skills development. Here we will use an amended version so pay close attention to the instructions in this assignment and do specifically as each task asks. Today we will be running a correlation between a measure of Fairness and Satisfaction versus a measure of Support for Redistribution.

<!--chapter:end:09-s02-lab09d.Rmd-->



## Solutions to Questions
### Correlations Application
#### Task 1
#### Task 2
#### Task 3
#### Task 4
#### Task 5
#### Task 6
#### Task 7
#### Task 8
#### Task 9
### Practice Your Skills

<!--chapter:end:09-s02-lab09e.Rmd-->



## Additional Material
### Checking for outliers with z-scores {-}
### A different approach to making a correlation table {-}
### Comparing Correlations {-}

<!--chapter:end:09-s02-lab09f.Rmd-->


# Simple Regression

Placeholder


## Activity 1: Setup {#regression-a1}
## Activity 2: Tidy the data {#regression-a2}
## Activity 3: Calculate mean anxiety for each student {#regression-a3}
## Activity 4: Join the datasets together {#regression-a4}
## Activity 5: Calculate descriptives for the variables overall {#regression-a5}
## Activity 6: Visualisations {#regression-a6}
## Activity 7: Run the regression {#regression-a7}
## Activity 8: Assumption checking {#regression-a8}
## Activity 9: Power and effect size {#regression-a9}
## Activity 10: Write-up {#regression-a10}
## Solutions to Activities {#regression-sols}
### Activity 1 {#regression-a1sol}
### Activity 2 {#regression-a2sol}
### Activity 3 {#regression-a3sol}
### Activity 4 {#regression-a4sol}
### Activity 6 {#regression-a6sol}

<!--chapter:end:10-s02-lab10a.Rmd-->


# Multiple Regression

Placeholder


## Activity 1: Set-up {#mulregression-a1}
## Activity 2: Look at the data {#mulregression-a2}
## Activity 3: Compute the well-being score for each respondent {#mulregression-a3}
## Activity 4: Visualise the relationship {#mulregression-a4}
## Activity 5: Smartphone and well-being for boys and girls {#mulregression-a5}
## Activity 6: Mean-centering variables {#mulregression-a6}
## Activity 7: Visualise the relationship {#mulregression-a7}
## Activity 8: Running the regression {#mulregression-a8}
## Activity 9: Assumption checking {#mulregression-a9}
## Activity 10: Power and effect size {#mulregression-a10}
## Activity 11: Making predictions {#mulregression-a11}
## Activity 12: Write-up {#mulregression-a12}
## Solutions to Activities {#mulregression-sols}
### Activity 3 {#mulregression-a3sol}
### Activity 5 {#mulregression-a5sol}
### Activity 6 {#mulregression-a6sol}
### Activity 7 {#mulregression-a7sol}
### Activity 8 {#mulregression-a8sol}
### Activity 9 {#mulregression-a9sol}
### Activity 10 {#mulregression-a10sol}
### Activity 11 {#mulregression-a11sol}

<!--chapter:end:11-s02-lab11a.Rmd-->


# One-way ANOVA

Placeholder


## Background: Intrusive memories
## Activity 1: Set-up {#anova-a1}  
## Activity 2: Data wrangling {#anova-a2}  
## Activity 3: Numbers and factors {#anova-a3}
## Activity 4: Create summary statistics {#anova-a4}
## Activity 6: One-way ANOVA {#anova-a6}
## Activity 7: Assumption checking {#anova-a7}
## Activity 9: Power and effect size {#anova-a9}
## Activity 10: Write-up {#anova-a10}
## Solutions to Activities {#anova-sols}
### Activity 1 {#anova-1sol}
### Activity 2 {#anova-a2sol}
### Activity 4 {#anova-a4sol}
### Activity 5 {#anova-a5sol}

<!--chapter:end:12-s02-lab12a.Rmd-->


# Factorial ANOVA

Placeholder


## Activity 1: Set-up {#factorial-a1}
## Activity 2: Descriptive statistics {#factorial-a2}
## Activity 3: Violin-boxplots {#factorial-a3}
## Activity 4: Interaction plots {#factorial-a4}
## Activity 5: ANOVA {#factorial-a5}
## Activity 6: Assumption checking {#factorial-a6}
## Activity 7: Post-hoc tests {#factorial-a7}
## Activity 8: Write-up {#factorial-a8}
## Activity 9: Transforming data {#factorial-a9}
## Practice Your Skills
### Task 1A: Libraries {#Ch13AssignQueT1A}
### Task 1B: Loading in the data {#Ch13AssignQueT1B}
### Task 2: Calculate cell means {#Ch13AssignQueT2}
### Task 3: Marginal means for sex {#Ch13AssignQueT3}
### Task 4: Marginal means for condition {#Ch13AssignQueT4}
### Task 5: Interaction plot {#Ch13AssignQueT5}
### Task 6: Recap Question 1 {#Ch13AssignQueT6}
### Task 7: Recap Question 2 {#Ch13AssignQueT7}
### Task 8: Recap Question 3 {#Ch13AssignQueT8}
### Task 9: Running the Factorial ANOVA {#Ch13AssignQueT9}
### Task 10: Interpreting the ANOVA output Question {#Ch13AssignQueT10}
### Task 11: Report your results {#Ch13AssignQueT11}
## Solutions to Activities {#factorial-sols}
### Chapter Activities 1-9
#### Activity 1 {#factorial-a1sol}
#### Activity 2 {#factorial-a2sol}
#### Activity 3 {#factorial-a3sol}
#### Activity 5 {#factorial-a5sol}
#### Activity 6 {#factorial-a6sol}
### Practice Your Skills Activities
#### Task 1A: Libraries
#### Task 1B: Loading in the data
#### Task 2: Calculate cell means for the cell means.
#### Task 3: Marginal means for sex
#### Task 4: Marginal means for condition
#### Task 5: Interaction plot
#### Task 6: Recap Question 1
#### Task 7: Recap Question 2
#### Task 8: Recap Question 3
#### Task 9: Running the factorial ANOVA
#### Task 10: Interpreting the ANOVA output Question
#### Task 11: Report your results

<!--chapter:end:13-s02-lab13a.Rmd-->

# (APPENDIX) Appendices {-} 

# Acknowledgements {-}

This book has been the work of many people, both staff and students within the School of Psychology & Neuroscience, University of Glasgow. A special mention, however, should go to the following people: Stephanie Boyle, Molly Burr, Morgan Daniel, Amalia Gomoiu, Kate Haining, Jesse Klein, Rebecca Lai, Steven McNair, Shannon McNee, Jennifer Murch, Jack Taylor, Jaimie Torrance, Ana Skolaris & Hollie Sneddon.

We hugely appreciate all comments and help in creating the material contained within this book.

A special shout-out to all students who worked through this book and pointed out errors or made suggestions: You helped us to consistently increase the quality of this book. Thanks.


<!-- # Stats by Hand {-} -->

<!-- There is an accompanying workbook in development that looks at calculating statistics by hand. If you are interested in it (though it is in development stages so is rough) you can see it here: [The Handy Workbook for Stats by Hand](https://psyteachr.github.io/handyworkbook/){target="_blank"} -->

<!--chapter:end:appendix-0.Rmd-->


# Installing `R` {#installing-r}

Placeholder


## Installing Base R
## Installing RStudio
## RStudio Settings
## Installing LaTeX

<!--chapter:end:appendix-a-installing-r.Rmd-->


# Updating R, RStudio, and packages

Placeholder


## Updating RStudio
## Updating packages
## Updating R

<!--chapter:end:appendix-b-updating-r.Rmd-->

# Exporting files from the server

If you are using the R server, you may need to export files to share them with other people or submit them for your assignments.

* First, make sure you have saved any changes you have made to the file. Do this by clicking "File - Save", Ctrl + S, or clicking the save icon. If all your changes have been saved, the save icon will be greyed out. If there are new unsaved changes, you will be able to click the icon.
* Select the file you and to download in the files pane (bottom right) by ticking the box next to it, then click "More - Export" and save the file to your computer.
* If you do not have R installed, DO NOT try to open it on your computer. If you do, it will open in Word, Endnote or similar, and it may corrupt your code. Only open the file if you have R and R Studio installed.
* If you want to double check that this file is definitely the right one to submit for an assignment, you can re-upload it to the server and open it again to make sure it has the answers in it.

<!--chapter:end:appendix-c-exporting-server.Rmd-->


# Symbols {#symbols}

Placeholder



<!--chapter:end:appendix-d-symbols.Rmd-->

# License {-}

This book is licensed under Creative Commons Attribution-ShareAlike 4.0 International License [(CC-BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/){target="_blank"}. You are free to share and adapt this book. You must give appropriate credit, provide a link to the license, and indicate if changes were made. If you adapt the material, you must distribute your contributions under the same license as the original. 

<!--chapter:end:appendix-y-license.Rmd-->

# References {-}


<!--chapter:end:appendix-z-refs.Rmd-->

