# Learning DAX
Learning DAX by translating examples from CALCULATE syntax to the VAR/RETURN syntax.

I'm going through The Definitive Guide to DAX (2nd ed.) by Marco Russo and Alberto Ferrari. The code examples can be found [here](https://www.sqlbi.com/books/the-definitive-guide-to-dax-2nd-edition/companion/).

My point of view is not to say that you shouldn't use CALCULATE in your DAX code. But I found that the VAR/RETURN syntax (that you can see examples of in the .pbix files in this repo) is more intuitive for the way I like to write code. For the past five years, I've been mainly writing R (tidyverse) and SQL code. I'm sure that has influenced the way I approach DAX.

You be the judge, obviously, but I think the biggest difference between the two is that the VAR/RETURN syntax is more verbose. You have to explicitly tell what you want to happen. I prefer it to the more blackbox-y approach of using CALCULATE. I've also been told that CALCULATE originated before variables did. So back in the day, it was probably the only way. Not anymore, though.

## Comments on the code by Chapter

### Chapter 5 - Understanding CALCULATE and CALCULATETABLE

- Most of the translated code is in the Sales table
  - Except for Example 35 where the code will be found in the Product table
- The measures with the VAR/RETURN syntax have been named with the NO CALCULATE postfix

## Acknowledgments and further viewing

I would like to thank [Brian Julius](https://www.linkedin.com/in/brianjuliusdc/) and [Greg Deckler](https://www.linkedin.com/in/gregdeckler/) for introducing me to this alternative approach to DAX.

If you're interested, I suggest watching the videos on Greg's YouTube channel called [DAX for Humans](https://www.youtube.com/watch?v=Gqei-cQ-P7c&list=PL-pfHAlWLrbTXJrmu9bpD2rSzzGxf5gWY). Very helpful and easy to follow!
