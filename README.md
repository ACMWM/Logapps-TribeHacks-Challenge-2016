# Logapps-TribeHacks-Challenge-2016
![alt tag](http://static1.squarespace.com/static/558ad739e4b0691bf6ef2d36/t/55fc3e89e4b039f7eac27f68/1459186648029/?format=400w)

Logapps invites your team to solve the following two-part problem set within the guidelines. By the end of this exercise, your team will gain knowledge in Natural Language Processing (NLP) and string searching algorithms.  No prior knowledge in NLP is required, but teammates should have reasonable programming ability using Java or Python and making tables and graphing data structures. 

We suggest TribeHack participants download NLTK (http://www.nltk.org/) and view the Stanford CoreNLP suite of tools (http://stanfordnlp.github.io/CoreNLP/index.html).


## Problem

### Part 1

Using NLP in Java or Python decompose the paragraphs and sentences attached in Appendix 1 
[to include subject(s), verb(s), object(s), etc.] and export to a table using the same format in example 1.

* See [Table 2](#table-2) for clarification. 

### Part 2

Using Table 1 Key Words and the Business Rules below, expand on the table generated in part 1 but with the summation of the numbers within each column. 

* See [Table 3](#table-3) for clarification. 

## Business Rules

1. Must use Java or Python
2. Use NLP to breakdown the sentences 
3. If the sentence has the same verb as the preceding sentence, then do not account for the verb 
numbers from the reference table for the second sentence
4. If the proper name (noun) is similar to a key word verb, then do not count it
5. If the object noun is similar to a key word verb, then do not count it
6. Any keyword verb that follows within brackets, then do not count it

## Inputs

1. [The Global Differential GPS System – NASA write up – Appendix 1. Inclusive of Functional 
Overview, Usability, Quality Factors and Creativity sections.](https://github.com/ACMWM/Logapps-TribeHacks-Challenge-2016/blob/master/appendix1.txt)

2. [Table 1](https://github.com/ACMWM/Logapps-TribeHacks-Challenge-2016/blob/master/table1.csv)

## Outputs

1. A table for the [Global Differential GPS System](https://github.com/ACMWM/Logapps-TribeHacks-Challenge-2016/blob/master/appendix1.txt) sentences breakdown. The table at minimum must show:
	* Sentence unique ID
	* Verb(s)
	* Subject(s)
	* Object(s)

2. An expanded table to [Part 1](#part-1) to include 7 categories, in the format of [Table 3](#table-3).

### Sample Outputs

#### Example 1 (Part 1 of the Problem)

##### Table 2

| Para. # | Sent. # | Subject          | Verbs                                               | Actual Verbs          | Remaining                                                                              |                                                  |
|---------|---------|------------------|-----------------------------------------------------|-----------------------|----------------------------------------------------------------------------------------|--------------------------------------------------|
| 1       | 1       | The GDGPS        | Is Drive Power Set Develop Complete Possess Capable | Drive Develop Possess | Powerful software set Completely in house at JPL Many unique features and capabilities |                                                  |
| 1       | 2       | The C++ Software | Evolve Develop Lead Process Package Is              | Evolve Develop        | "From one of the world's leading GPS data processing and analysis software packages     JPL's GIPCY-OASIS and its real time version RTG" |

#### Example 2 (Part 2 of the Problem)

##### Table 3

| Para. # | Sent. # | Subject          | Verbs                                               | Actual Verbs          | Remaining                                                                                                                           | Ctg. #1    | Ctg. #2   | Ctg. #3    | Ctg. #4    | Ctg. #5    | Ctg. #6    | Ctg. #7   |
|---------|---------|------------------|-----------------------------------------------------|-----------------------|-------------------------------------------------------------------------------------------------------------------------------------|------------|-----------|------------|------------|------------|------------|-----------|
| 1       | 1       | The GDGPS        | Is Drive Power Set Develop Complete Possess Capable | Drive Develop Possess | Powerful software set Completely in house at JPL Many unique features and capabilities                                              | 7+ 2+ 6=15 | 5+ 4+ 0=9 | 5+ 1+ 5=11 | 8+ 1+ 4=13 | 4+ 9+ 4=17 | 3+ 8+ 5=16 | 0+ 2+ 7=0 |
| 1       | 2       | The C++ Software | Evolve Develop Lead Process Package Is              | Evolve Develop**        | From one of the worldŐs leading GPS data processing and analysis software packages, JPLŐs GIPCY-OASIS and its real time version RTG | 4+ 0=4     | 1+ 0=1    | 2+ 0=2     | 9+ 0=9     | 6+ 0=6     | 2+ 0=2     | 6+ 0=6    |

** the key word ‘develop’ has been captured in the father/first sentence (within the same paragraph), thus the values for it in category 1-7 will not be added.

## Judging Criterias:

##### 1. Innovation:
	* Does your application think outside the box?
##### 2. Business Value:
	* Does the business application create value?
##### 3. Use:
	* Does the application solve the problem?  Are there extra features and capabilities of the code?
##### 4. Followed Rules:
	* Did the group provide solutions within the established guidelines?


### Submission Guidelines:
Code and output must be on Github and submitted on DevPost for review.

### Questions?
For clarification on the problem, please contact Kevin McKeel at mckeel@logapps.com or 703.919.6359.
