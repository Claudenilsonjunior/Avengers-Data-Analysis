# Avengers Data Analysis

## Table of Contents
1. [Introduction](#introduction)
2. [Questions](#questions)
3. [Data Description](#data-description)
4. [Analysis](#analysis)
   - [Question 1: How many Avengers have died at least once?](#question-1-how-many-avengers-have-died-at-least-once)
   - [Question 2: Top 10 Avengers Who Died the Most](#question-2-top-10-avengers-who-died-the-most)
   - [Question 3: Did all characters die at some point?](#question-3-did-all-characters-die-at-some-point)
   - [Question 4: Is there a difference in mortality between characters of different genders?](#question-4-is-there-a-difference-in-mortality-between-characters-of-different-genders)
   - [Question 5: What is the relationship between the number of appearances and deaths?](#question-5-what-is-the-relationship-between-the-number-of-appearances-and-deaths)
   - [Question 6: Has mortality changed over the years?](#question-6-has-mortality-changed-over-the-years)
   - [Question 7: Are there Avengers who died multiple times and returned?](#question-7-are-there-avengers-who-died-multiple-times-and-returned)
   - [Question 8: Which characters are currently active or inactive?](#question-8-which-characters-are-currently-active-or-inactive)
   - [Question 9: Who are the characters with the most appearances who never died?](#question-9-who-are-the-characters-with-the-most-appearances-who-never-died)
   - [Question 10: What is the average time since a character joined the Avengers?](#question-10-what-is-the-average-time-since-a-character-joined-the-avengers)
5. [Conclusion](#conclusion)

## Introduction
This project analyzes data on Avengers characters, exploring their deaths, returns, and other statistics.

## Questions
1. How many Avengers have died at least once?
2. Top 10 Avengers Who Died the Most 
3. What is the distribution of deaths among characters?
4. Did all characters die at some point?
5. Is there a difference in mortality between characters of different genders?
6. What is the relationship between the number of appearances and deaths?
7. Has mortality changed over the years?
8. Are there Avengers who died multiple times and returned?
9. Which characters are currently active or inactive?
10. Who are the characters with the most appearances who never died?
11. What is the average time since a character joined the Avengers?

## Data Description
- The dataset includes various attributes such as name, appearances, deaths, returns, and gender of the Avengers.

### Dataset Dictionary

Header | Definition
---|---------
`URL`| The URL of the comic character on the Marvel Wikia
`Name/Alias` | The full name or alias of the character
`Appearances` | The number of comic books that character appeared in as of April 30 
`Current?` | Is the member currently active on an avengers affiliated team?
`Gender` | The recorded gender of the character
`Probationary` | Sometimes the character was given probationary status as an Avenger, this is the date that happened
`Full/Reserve` | The month and year the character was introduced as a full or reserve member of the Avengers
`Year` | The year the character was introduced as a full or reserve member of the Avengers
`Years since joining` | 2015 minus the year
`Honorary` | The status of the avenger, if they were given "Honorary" Avenger status, if they are simply in the "Academy," or "Full" otherwise
`Death1` | Yes if the Avenger died, No if not. 
`Return1` | Yes if the Avenger returned from their first death, No if  they did not, blank if not applicable
`Death2` | Yes if the Avenger died a second time after their revival, No if they did not, blank if not applicable
`Return2` | Yes if the Avenger returned from their second death, No if they did not, blank if not applicable
`Death3` | Yes if the Avenger died a third time after their second revival, No if they did not, blank if not applicable
`Return3` | Yes if the Avenger returned from their third death, No if they did not, blank if not applicable
`Death4` | Yes if the Avenger died a fourth time after their third revival, No if they did not, blank if not applicable
`Return4` | Yes if the Avenger returned from their fourth death, No if they did not, blank if not applicable
`Death5` | Yes if the Avenger died a fifth time after their fourth revival, No if they did not, blank if not applicable
`Return5` | Yes if the Avenger returned from their fifth death, No if they did not, blank if not applicable
`Notes` | Descriptions of deaths and resurrections. 

## Analysis

### Question 1: How many Avengers have died at least once?
**Result:** 69 Avengers died at least one time!

### Question 2: Top 10 Avengers Who Died the Most
![Death Distribution](path/to/death_distribution.png)

### Question 3: Did all characters die at some point? 
**Result:** Not all characters have died
**Number of characters who have not died:** 104
**Characters who never died:** [List here]

### Question 4: What is the distribution of deaths among characters?
![Death Distribution](path/to/death_distribution.png)

### Question 5: How many times did the Avengers return from death?
     - 0 returns: 127 characters
     - 1 return: 38 characters
     - 2 returns: 7 characters
     - 5 returns: 1 character
     
![Gender Mortality Distribution](path/to/gender_mortality.png)

### Question 6: Is there a difference in mortality between characters of different genders?
**Gender**
- Female: 67
- Male: 127

### Question 7: Has mortality changed over the years?
![Mortality Over the Years](path/to/mortality_over_years.png)

### Question 8: Are there Avengers who died multiple times and returned?
**Result:** 

  - Thor Odinson
  - Clinton Francis Barton
  - Heather Douglas
  - Matthew Liebowitz
  - Mar-Vell
  - Jocasta
  - Anthony Ludgate Druid
  - Marrina Smallwood
  - Ravonna Lexus Renslayer
  - Dennis Dunphy
  - Peter Benjamin Parker
  - Eric Kevin Masterson
  - Deathcry
  - Jonathan Hart
  - Maya Lopez
  - Ares

### Question 9: Which characters are currently active or inactive?
**Number of active avengers:** 82
**Number of inactive avengers:** 91 

**Active Characters:** [List here]
**Inactive Characters:** [List here]

### Question 10: Who are the top 10 characters with the most appearances who never died?
**Result:**

| Name                                | Appearances |
|-------------------------------------|-------------|
| Reed Richards                       | 2125        |
| Henry P. McCoy                     | 1886        |
| Susan Richards (nee Storm)         | 1761        |
| Ororo Munroe                       | 1598        |
| Matt Murdock                       | 1375        |
| Doctor Stephen Vincent Strange      | 1324        |
| Carol Susan Jane Danvers           | 935         |
| Carl Lucas                         | 886         |
| Anna Marie                         | 877         |
| T'Challa                           | 780         |



### Question 11: What is the average time (in years) since a character joined the Avengers?
**Result:** The average time (in years) since a character joined the Avengers is: 26.55 years!

## Conclusion
In this analysis, we explored various aspects of Avengers characters, providing insights into their mortality and activity status.

