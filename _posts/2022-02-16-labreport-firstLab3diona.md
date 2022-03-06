---
layout: post
title: Lab3 Diona Espinosa
subtitle: ENG 612 Prof.Thomas
cover-img: 
thumbnail-img: 
share-img: 
tags: [Lab3, labreport, regex]
---

## Regex

**Exploring Regular Expressions**

Here’s the data:

The Epoch Times, New York ed.; New York (NY)
"La Voz Bilingüe"; Denver, Colo.
Jewish Advocate; Boston
Washington Informer; Washington, [D.C.]
News from Indian Country; Hayward, WI.?
Afro - American, 5 Star edition; Baltimore, Md.
Diverse Issues in Higher Education; Fairfax Virginia
The Gay &amp; Lesbian Review Worldwide; Boston, MA
"The Hispanic Outlook in Higher Education; [Paramus N.J

1.	Regex to delete quotation marks: "[^0-9a-zA-Z]"   Substitution: [\,]
If we use this expression "[^0-9a-zA-Z]"   the blank space is included. Then, if we use the substitute regex “\,”do this, we can notice that the substitution occurs for all quotation marks, even tab space.  
Next, if we use this expression "[^0-9a-zA-Z]" and later we use the substitute regex “\t”, we can notice that we are replacing the quotation marks in the test string data with nothing.  
2.	Now, if we copy the output and paste that output into the “Test String” box, we will see only highlighted blank spaces. 

## Notebook Entry 3

The work with Regular expressions this week was hard to do it, and hard to understand. For me, it was difficult to find a regex to eliminate “the blank space” character. But definitely, we could practice the idea of “cleaning data” by eliminating or substituting some info or data from the original data. 

I recognize that by doing this and practicing with this tool more consistently we can avoid time-consuming when we have huge amount of data to work with in a particular work or research. Also, this cleaning could help me to understand how difficult could be to find a particular information in a big dataset. In other words, this could avoid the messiness designing and conceiving a database. However, this idea about “mess” make thing in that we already conceive, or we have a preconception about what is an organized work, this means that we assume that a kind of information goes in a kind of place, already has a “right” destination or location; like Katie Rawson and Trevor Muñoz explain “it supposes things already have a rightful place, but they are not in it—like socks on the bedroom floor rather than in the bureau or the hamper.”

On the other hand, as Rawson and Muñoz also argue, “as researchers working in the domain of data-intensive humanities research, we have found that these assumptions intensify suspicions about knowledge claims that are based on “data.” In fields where data-intensive work has a longer history, researchers have developed paradigms and practices that provide de facto definitions of data cleaning (Newman, Ellisman, and Orcutt). In the humanities, however, these bounds are still unformed. Yet the humanities cannot import paradigms and practices wholesale from other fields, whether from “technoscience” or the nearer “social” sciences, without risking the foreclosure of specific and valuable humanistic modes of producing knowledge. If we are interested in working with data, and we accept that there is something in our work with data that is like what other fields might call “data cleaning,” we have no choice but to try to articulate both what it is and what it means in terms of how humanists make knowledge.” 

Data cleaning encourage us as researchers to think about what our standpoint, horizon and perspective with the use and finality about the data is is that we are using. We cannot simplify the work with assumptions and conceptions from other fields, because as humanists we cannot work with some standardizes categories from the technoscience, as the quote above explains. We need to particularize and take into account “that” data that is marginalized (maybe discriminated) embedded and reduced to a category that even do not pay attention to diversity. 

However, this exercise (even Lab3) of organizing the data, remarks us the idea about how the researchers follow strategics and rationalities for the structuration of the info that will emphasize the possibility of practicing power. Data cleaning is the implementation of technical solutions to a particular -imagined- technical problem, and algorithms like regex can definitely help to clarify it. But, as a quantitative and also qualitative exercise, the visualization of data, for example, will be mediated by some patterns and we as scholars and researchers need to be clear about the main goal in the research in order to avoid some “problem” or “occlusion” that can obscure important features or info, in general. As Catherine D'Ignazio and Lauren Klein explain “whether or not you think data scientists are sexy (they are), and whether or not you think janitors should be offended by this classist reference (we all should be), certain assumptions and anxieties remain consistent across these different articulations about the need for tidiness, cleanliness, and order, and the qualities of the people who should be doing this work. They must be able to tame the chaos of information overload. They must “scrub” and “cleanse” dirty data. And they must undertake deliberate action—either extraordinary or mundane—to put data back in their proper place.”  Then, I would like to finish my reflection saying that “transparency” and “cleanness” can be paradoxically blurred and manipulated terms and remain us how knowledge is controlled and constructive or deconstructive. Priority and visibility should be two terms attached to the last two at the moment to critically analyze data.  


**Sources:**

Catherine D’Ignazio and Lauren F. Klein, “Ch. 5: Unicorns, Janitors, Ninjas, Wizards, and Rock Stars” from Data Feminism (2020)

Katie Rawson and Trevor Muñoz, “Against Cleaning,” from Debates in the Digital Humanities 2019 (2019)
