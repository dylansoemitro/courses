Computational Linguistics, Fall 2020

# Homework 1 (25 points)

Due Friday, September 18

Topics: Regular expressions (Lecture Notes, J&M 2.1), Levenshtein distance (J&M 2.5), Lemmatization and Stemming (J&M 2.4), Tokenization (2.4.1), I/O redirection

1. (10 points) Using either Python 3 or `grep`, complete 2.1 and 2.2 from J&M.   You may use any resources you find useful, in the textbook or elsewhere, for doing this.  

   

   (15 points) In a PDF file, created in $\LaTeX$ or [Markdown](https://www.markdownguide.org/tools/typora/), concisely answer the following questions.  You are encouraged but not required to use outside sources for these questions, but if you do, cite them.
   
2. 1. (5 points) What are some uses of edit distance outside of human language?  
   2. (5 points) When might one prefer lemmatization over stemming and vice versa?
   3. (5 points) Tokenization is easy for languages that use spaces.  How might it work for unsegmented languages, such as Chinese or Japanese?

   ## Deliverables

   For part (1), include the following:

   * A file of test cases that you create, called `cases.txt`.
   * Your `hw1.py` or `hw1.sh` file, which will test for all of the patterns assigned when run.

   If you use `grep`, place your code in a shell script called `hw1.sh`.  I should be able to run, for example:

   ```bash
   sh hw1.sh
   ```

   If you use Python, read the input from `stdin`.  If I run your code, I should be able to to run, for example:

   ```bash
   python3 hw1.py < cases.text
   ```

   to see the results.

   For part (2), include your PDF file.

**Submit all of your files to Moodle in a `familyname_givenname_hw1.tar.gz` file containing a directory called familyname_givenname (except with your actual names)**.

This means that if I run:

```bash
tar xvf grissom_alvin_hw1.tar.gz
```

a directory called `grissom_alvin` should be created, and it should contain the files for your submission.  To do this, your files need to place your files in the directory first and then compress the directory.  See this link for examples: https://www.educative.io/edpresso/how-to-gzip-a-directory-in-linux

Be sure to test this before you submit.