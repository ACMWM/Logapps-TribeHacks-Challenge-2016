# Logapps-TribeHacks-Challenge-2016
![alt tag](http://static1.squarespace.com/static/558ad739e4b0691bf6ef2d36/t/55fc3e89e4b039f7eac27f68/1459186648029/?format=400w)

Logapps invites your team to solve the following two-part problem set within the guidelines. By the end of this exercise, your team will gain knowledge in Natural Language Processing (NLP) and string searching algorithms.  No prior knowledge in NLP is required, but teammates should have reasonable programming ability using Java or Python and making tables and graphing data structures. 


## Problem

### Part 1

Using NLP in Java or Python decompose the paragraphs and sentences attached in Appendix 1 
[to include subject(s), verb(s), object(s), etc.] and export to a table using the same format in example 1.

* See table 2 on page 3 for clarification. 

### Part 2

Using Table 1 Key Words on page 2 and the Business Rules below, expand on the table generated in part 1 but with the summation of the numbers within each column. 

* See table 3 on page 4 for clarification. 

## Business Rules

1. Must use Java or Python
2. Use NLP to breakdown the sentences 
3. If the sentence has the same verb as the preceding sentence, then do not account for the verb 
numbers from the reference table for the second sentence
4. If the proper name (noun) is similar to a key word verb, then do not count it
5. If the object noun is similar to a key word verb, then do not count it
6. Any keyword verb that follows within brackets, then do not count it

## Inputs

1. The Global Differential GPS System – NASA write up – Page 5, Appendix 1. Inclusive of Functional 
Overview, Usability, Quality Factors and Creativity sections.

2. Table 1

## Outputs

1. A table for the Global Differential GPS System sentences breakdown. The table at minimum must show:
	* Sentence unique ID 
	* Verb(s)
	* Subject(s)
	* Object(s)

2. An expanded table to part 1 to include 7 categories, in the format of Table 3.



## Tables

### Table 1
| Key Word    | Category 1 | Category 2 | Category 3 | Category 4 | Category 5 | Category 6 | Category 7 |
|-------------|------------|------------|------------|------------|------------|------------|------------|
| Accommodate | 8          | 8          | 7          | 3          | 1          | 1          | 2          |
| Achieve     | 0          | 2          | 2          | 3          | 6          | 5          | 7          |
| Adapt       | 9          | 3          | 5          | 6          | 2          | 4          | 3          |
| Add         | 8          | 8          | 0          | 4          | 2          | 8          | 7          |
| Analyze     | 5          | 5          | 3          | 0          | 4          | 7          | 4          |
| Capable     | 8          | 7          | 2          | 4          | 9          | 8          | 6          |
| Complete    | 5          | 2          | 3          | 2          | 5          | 4          | 9          |
| Compress    | 1          | 3          | 0          | 2          | 8          | 9          | 3          |
| Control     | 2          | 1          | 6          | 3          | 3          | 0          | 5          |
| Delay       | 2          | 3          | 2          | 6          | 8          | 4          | 9          |
| Demand      | 8          | 6          | 1          | 3          | 1          | 7          | 0          |
| Design      | 5          | 1          | 3          | 9          | 7          | 3          | 5          |
| Determine   | 9          | 7          | 5          | 0          | 8          | 6          | 8          |
| Develop     | 2          | 4          | 1          | 1          | 9          | 8          | 2          |
| Display     | 8          | 3          | 9          | 2          | 7          | 4          | 5          |
| Drive       | 7          | 5          | 5          | 8          | 4          | 3          | 0          |
| Embed       | 7          | 5          | 8          | 1          | 9          | 7          | 8          |
| Enable      | 9          | 6          | 4          | 2          | 1          | 7          | 5          |
| Estimate    | 3          | 2          | 7          | 5          | 2          | 8          | 4          |
| Evolve      | 4          | 1          | 2          | 9          | 6          | 2          | 6          |
| Exploit     | 7          | 4          | 3          | 5          | 5          | 6          | 1          |
| Ground      | 3          | 8          | 8          | 5          | 5          | 2          | 1          |
| Guarantee   | 7          | 3          | 1          | 6          | 1          | 8          | 2          |
| Handle      | 7          | 6          | 1          | 6          | 5          | 3          | 3          |
| Integrate   | 8          | 6          | 0          | 5          | 6          | 3          | 4          |
| Lead        | 3          | 2          | 1          | 0          | 8          | 9          | 5          |
| Maintain    | 9          | 6          | 2          | 1          | 4          | 7          | 5          |
| Model       | 4          | 6          | 8          | 2          | 4          | 8          | 5          |
| Monitor     | 6          | 7          | 9          | 1          | 2          | 2          | 6          |
| Operate     | 1          | 1          | 5          | 7          | 1          | 8          | 4          |
| Orbit       | 7          | 5          | 4          | 1          | 6          | 1          | 7          |
| Perform     | 3          | 6          | 3          | 1          | 5          | 1          | 6          |
| Playback    | 6          | 8          | 9          | 5          | 7          | 8          | 6          |
| Portable    | 6          | 7          | 6          | 5          | 9          | 3          | 6          |
| Position    | 7          | 8          | 5          | 2          | 1          | 1          | 7          |
| Possess     | 6          | 0          | 5          | 4          | 4          | 5          | 7          |
| Post        | 1          | 1          | 1          | 2          | 2          | 3          | 4          |
| Process     | 2          | 4          | 6          | 2          | 3          | 2          | 8          |
| Protect     | 3          | 5          | 7          | 3          | 8          | 4          | 7          |
| Receive     | 7          | 1          | 1          | 8          | 5          | 9          | 4          |
| Record      | 4          | 7          | 1          | 6          | 6          | 8          | 1          |
| Set         | 6          | 5          | 4          | 1          | 3          | 3          | 3          |
| Simulate    | 4          | 4          | 1          | 7          | 1          | 7          | 8          |
| Support     | 2          | 4          | 9          | 7          | 7          | 2          | 8          |
| Test        | 0          | 3          | 3          | 7          | 2          | 1          | 7          |
| Track       | 1          | 4          | 4          | 9          | 2          | 4          | 4          |
| Use         | 7          | 6          | 8          | 7          | 1          | 0          | 8          |
| Work        | 3          | 7          | 3          | 8          | 6          | 3          | 5          |

