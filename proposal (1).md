# Proposal

## What will (likely) be the title of your project?

Replication of Machine Learning for Food Processing in Python

## In just a sentence or two, summarize your project. (E.g., "A website that lets you buy and sell stocks.")

A machine learning that identifies the level of processing of foods based on a nutrient list.

## In a paragraph or more, detail your project. What will your software do? What features will it have? How will it be executed?

My project will be a machine learning algorithm in Python that will take in nutrition facts of different foods and be able to determine the level of processing of each food. I will adapt the R code created by Menichetti and colleagues (2023) to be used in Python, which is available on Github. I will also use the Food and Nutrient Database for Dietary Studies (FNDDS) 2019-2020 release, whereas these researchers used the 2009-2010 release, changing the amount of nutrient values and training dataset. I will train the machine learning, using the algorithm provided by the researchers, to give an output of one of four NOVA classification labels: raw, minimally processed, processed culinary ingredient, or ultra processed. This will be determined using a continuous food processing variable where 0 = raw and and 1 = ultra processed. 

Menichetti, G., Ravandi, B., Mozaffarian, D. et al. Machine learning prediction of the degree of food processing. Nat Commun 14, 2312 (2023). https://doi.org/10.1038/s41467-023-37457-1

## If planning to combine 1051's final project with another course's final project, with which other course? And which aspect(s) of your proposed project would relate to 1051, and which aspect(s) would relate to the other course?

I am not combining this final project with a course but it is applicable to the research lab I work in, the Temple Eating Disorders program, and a project I will be working on over the summer for the Diamond Research Scholars program. The summer project involves verifying that the machine learning that already exists works and is the most effective way to identify processing levels of food. This project will help me better understand how the machine learning works and could help me to create a better machine learning to test in the future.

## If planning to collaborate with 1 or 2 classmates for the final project, list their names, email addresses, and the names of their assigned TAs below.

TODO, if applicable

## In the world of software, most everything takes longer to implement than you expect. And so it's not uncommon to accomplish less in a fixed amount of time than you hope.

### In a sentence (or list of features), define a GOOD outcome for your final project. I.e., what WILL you accomplish no matter what?

No matter what, I will learn about the process of creating a machine learning algorithm in Python and be able to recreate at least part of the project. Alternatively, I could adapt the previous code in R to use the newer FNDDS.

### In a sentence (or list of features), define a BETTER outcome for your final project. I.e., what do you THINK you can accomplish before the final project's deadline?

I think I can recreate the machine learning algorithm in Python exactly as the previous researchers did in R.

### In a sentence (or list of features), define a BEST outcome for your final project. I.e., what do you HOPE to accomplish before the final project's deadline?

The best outcome for this project would be to create a machine learning algorithm in Python that can identifying the process level of food based on the most current FNDDS.

## In a paragraph or more, outline your next steps. What new skills will you need to acquire? What topics will you need to research? If working with one of two classmates, who will do what?

I will need to study the paper by Menichetti and colleagues (2023) more closely and look into training machine learning algorithms in Python. I will download the code used by the previous researchers and study that as well. Then, I will figure out how to access the current FNDDS and download it so I can use it in my project. Next, I will work on adapting the code, training the model, testing it, etc.
