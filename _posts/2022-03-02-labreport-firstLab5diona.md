---
layout: post
title: Lab5 Diona Espinosa
subtitle: ENG 612 Prof.Thomas
cover-img:
thumbnail-img: 
share-img: 
tags: [Lab5, labreport, Python]
---

## Python and the questions

**WORK IN PROGRESS**
1- What do you notice about how this function has split the string “Okay, okay, ladies, now let’s get in formation, cause I slay”? What has it done that isn’t quite right, and why has it done this? Write down your response in your notes document.
When we split the string “Okay, okay, ladies, now let’s get in formation, cause I slay”, the function divided the phrase into each individual words, but the algorithm recognized the words “let’s” as two different words, like “let” and “s”. The latter happened because the function read “let’s” with the apostrophe as an indication of a new ending of a word. In other words, it was unable to identify the punctuation marks like the function could recognize with period or comma. In order to understand why it has done this, we need to understand the command behind the function. The algorithm was designed for a machine which only identified that every term only contains letter, a non-alphabetical character is read as a new word.

2- What happened? Did it work as you expected? If not, what happened that you didn’t expect? Write down your response in your notes document.
It did work as expected. The function identified the punctuation ending the sentence as an additional character and all the words were listed individually. 

3- Describe the output of this script (the dataframe that displays after the above cell finishes running). Remember that this is the same output as the “vir-ver-counts-specific” spreadsheet in our Lab5 Google drive folder, only for just 10 texts. What is this dataframe showing us? Write down your response in your notes document.
The dataset shows the number of occurrences of “virtu” and “vertu” per document. It also gives us author, date of birth and death, and date of publication of the document. This function demonstrate the importance of coding in an specific order to get an specific  or accurate result. 

4- Look at the below lines from the compare_counts_specific function above. These lines use regular expressions to do something to the value of the <date> field in an xml file (if the contents of the <date> field meet certain conditions, that is). What are these lines doing?




**Notebook entry**

**Lab6 Dataset**

For Lab 6 I will work with Race Film Database. This database contains information on films, actors, production companies, and other aspects of early silent-era African American race films. 
