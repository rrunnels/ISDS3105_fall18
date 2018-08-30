Assignment 2
================
Your name

The goal of this practice is to improve your understanding of vectors and how to manipulate them. The data we use are the prices of the [2017 Big Mac Index](http://www.economist.com/content/big-mac-index).

For each question, please create a new chunck with your reponse. Use narratives to comment the output whenever the question requires to do so.

1.  Edit the code below to assign country names to the vector `countries` and prices to the vector `prices`. Hide the code below when you knit (check the Rmarkdown cheatsheet to find the appropriate chunk option to hide code).

2.  Use `typeof()` to report the type of both vectors.

<!-- -->

    ## [1] "character"

1.  Use `names()` to name the `prices` using `countries`. Show the first 5 values of your new vector

2.  Use `round()` to round the prices at the 3rd decimal. Overwrite `prices` with the rounded prices.

3.  Use indexing to report the prices for Canada, United States, Mexico

4.  Use inline code and the function `length()` to display the following sentence:

"The are x observations in the Big-Mac Index"

1.  Convert the prices from Dollar to Euro (1 Dollar = .83 Euro). In the narrative, comment about the property which allows you to combine a vector of length 1 (the exchange rate) with a vector of length 56 (the prices).

-   Could you use the vector `rep(.83, 28)` to do the same?
-   Could you use the vector `rep(.83, 112)` to do the same?
-   Would `rep(.83, 45)` also work? Why?

1.  In your narrative, mention that we are going to drop the 46th element. Use dynamic code to report the country that will drop.

2.  Overwrite the vector of prices with a new vector without observation 46. Use `length()` to make sure you have one observation less.

3.  Knit, commit and push to your GitHub repo `assignment`. Then submit the link to the *assignment folder* on Moodle.
