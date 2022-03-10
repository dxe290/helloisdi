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


1- What do you notice about how this function has split the string “Okay, okay, ladies, now let’s get in formation, cause I slay”? What has it done that isn’t quite right, and why has it done this? Write down your response in your notes document.

When we split the string “Okay, okay, ladies, now let’s get in formation, cause I slay”, the function divided the phrase into each individual words, but the algorithm recognized the words “let’s” as two different words, like “let” and “s”. The latter happened because the function read “let’s” with the apostrophe as an indication of a new ending of a word. In other words, it was unable to identify the punctuation marks like the function could recognize with period or comma. In order to understand why it has done this, we need to understand the command behind the function. The algorithm was designed for a machine which only identified that every term only contains letter, a non-alphabetical character is read as a new word.

2- What happened? Did it work as you expected? If not, what happened that you didn’t expect? Write down your response in your notes document.

It did work as expected. The function identified the punctuation ending the sentence as an additional character and all the words were listed individually. 

3- Describe the output of this script (the dataframe that displays after the above cell finishes running). Remember that this is the same output as the “vir-ver-counts-specific” spreadsheet in our Lab5 Google drive folder, only for just 10 texts. What is this dataframe showing us? Write down your response in your notes document.

The dataset shows the number of occurrences of “virtu” and “vertu” per document. It also gives us author, date of birth and death, and date of publication of the document. This function demonstrate the importance of coding in an specific order to get an specific  or accurate result. 

4- Look at the below lines from the compare_counts_specific function above. These lines use regular expressions to do something to the value of the <date> field in an xml file (if the contents of the <date> field meet certain conditions, that is). What are these lines doing?

The expression “^” tells the computer to match the start of the string. When we use “^20” looks like it will match anything starting with “20”. Specifically, it identifies the year which was uploaded a document after the 2000. However, this date is not relevant, the important one is the one which the text was written. Then, the expression ^ function what it does is removing the date beginning with 20. 



**Notebook entry**

I definitely must confess that Python has been the tool more difficult to understand for me. Maybe, this is because I need more time exploring the platform and putting the options and algorithms in dialogue with any specific and target activity or research. However, it was really hepful to “touch” and “see” what an algorithm created by a human and process by a computational program is able to do in both senses, positively, or in contra with our interests. It also demonstrated me how important is coding in DH and programming languages. The DSC # 12 by Katherine Bowers, Quinn Dombrowski, and Roopika Risam, quotes in “The Magic of Python” how “playing” with it and “control” the computational processes inside the machine; but like this part contends there is not actual magic doing this. We are able to give instructions to the machine as a logic process, but the qualitative work important to DH and humanistic studies is to interpretate properly the results of functions, commands, expressions, algorithms. It is difficult to get know deeply how to code for an humanistic academic person, but what I learned is that we actually do not need to operate as wonderful engineers constructing complicated algorithms, what we indeed need is the meaning and purposes, the interpretated output of the computational operation: the transformation. (Schmidt)

I agree with Benjamin Schmidt when he argues that Digital Humanists do not need to understand an algorithm instead of the transformation. Therefore, he says that “the alternative to understanding the meaning of transformations is to use algorithms instrumentally”. In other words, I read from this that we need to be familiar with our corpus and data, this means the topic, discourse, perspectives. Nevertheless, in terms of the Python and algorithmic logic I should be confident in the way that DSC #12 contends “but you can only get there by practicing. And you’ll only practice if it’s worth it. And it’s only worth it if it’s the only way you, as a humanist, can do the things you want to do”. 


**Lab6 Dataset**

For Lab 6 I will work with Race Film Database. This database contains information on films, actors, production companies, and other aspects of early silent-era African American race films. 
Therefore, this dataset is relevant personally because of my research interest related to film studies. 