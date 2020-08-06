# Finding-Popular-Datascience-questions

The primary goal of this project is to answer to the question "What is it that people want to learn about in data science?" (as opposed to determining the most profitable content, for instance).

To answer this question, we look at the Stack Exchange websites that are relevant to our goal. Out of them, Data Science Stack Exchange (DSSE) is on the bottom 10 sites with respect to the metric - percentage of questions that received answers.

The fact that DSSE is a data science dedicated site (contrarily to the others), coupled with it having a lot of an unanswered questions, makes it an ideal candidate for this investigation. 

Now comes the challenge of accessing the data en masse required for our project. To our luck, Stack Exchange provides a public data base for each of its websites. We make use of this public database to collect the data we need for our analysis

After performing an intial data cleaning, we finalize on the indicators to look at to discern the popularity of topics in Datascience.

We determine the most popular tags by considering two different popularity proxies:

- for each tag we'll count how many times the tag was used
- how many times a questions that tag was viewed.

We will look for some ways to find relationships between pair of tags and between multiple tags.
By doing this, we see that most of the top tags are all intimately related with one central machine learning theme: deep learning.

At the glance of an eye, someone with sufficient domain knowledge can tell that the most popular topic at the moment, as shown by our analysis, is deep learning.
