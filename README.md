# Deep Learning with Multiple Objectives

Welcome to the lab! In this course, we will delve into one area of limitations of the current incarnation of deep learning technologies, while being optimistic about what is already possible.

<center><img width=400 src="labs/lab1/fig/fig2.png"></center>

There will be three separate modules. In the **first module** of the course, we will focus on learning in a stationary setting where the neural network learns each objective at the same time.  to We will have multiple competing objectives. Investigating this, we will better understand how deep neural networks are trained, and what are some limitations.

In the **second module**, we will focus on life-long learning. How do we learn over course of multiple tasks? This seems to be a necessary capability on the path to artificial general intelligence. 

In the **third module**, we highlight several solutions, most likely focusing on meta-learning, modularity (including computational computation). These two solutions were shown to help deep network learn multiple objectives both in the sequential and stationary setting.

## Important links

* [Main Spreadsheet](https://docs.google.com/spreadsheets/d/1tSO1ZlILxmD0LuMFZ3GLyJmtiJgMnJg0okkA43N_9AU/edit?usp=sharing)

* [Lab 1: 01-transfer](https://colab.research.google.com/drive/1y1Jh2JPjCgr6ccvmwk6iN6SaJWv143Qt?usp=sharing )

* [Lab 2: 02a-transformers](https://colab.research.google.com/drive/1qq8_7ycu4_rb4GS-BYkfKJlRbA1JVkUH?usp=sharing)

* [Lab 3: 02b-transformers](https://colab.research.google.com/drive/1pvXFV8o-G5Dr4Uwr5xVZSwB-Q7NJGlw6?usp=sharing)

* [Lab 4: 02c-transformers](https://colab.research.google.com/drive/1_RLws7wisxkCDv0Q4mfKVsLQKBFl-j6K?usp=sharing)

* [Anonymous Feedback](https://forms.gle/bP7EymPrknE3MKaT7) 
    - this is fully anonymous (you can fill it up without being logged to Google account)

* [Teams](https://teams.microsoft.com/l/team/19%3a4cbff8c281134f2f8997612796e81415%40thread.tacv2/conversations?groupId=c1c10036-51ad-4303-9d2f-fe9c6b666bb7&tenantId=eb0e26eb-bfbe-47d2-9e90-ebd2426dbceb) 
    - for lecture, and lab in case gather.town doesn't work

* [Whiteboard](https://cocreate-005.gather.town/r/tRrxB4rpgurrpc62y)

* [MiniProjects](https://docs.google.com/document/d/1vuCS-liGXCx7I0oSX4liyTFEUEYZtQszMgaTbg-aJWU/edit?usp=sharing)

Please do not enter your personal information when logging into Gather.town (or in the spreadsheet).

## Goal

* Understand challenges that deep learning faces

* Understand key classes of solutions to these challenges

    - Hands-on experience applying transfer learning models
 
* Understand key research directions that will shape the future of deep learning

    - Read and discuss papers
    
    - Reproduce one paper as a project 

## Tentative Outline

Disclaimer: This is likely to change. We just want to give you a general overview of the course.

Each lab is based on some key papers in the literature. The list of papers will be updated.

### Module 1: Static World
   
   - Lab 1: Transfer Learning
        * https://arxiv.org/abs/2010.11929
        * https://arxiv.org/abs/2005.14165
   
   - Lab 2: Implementing Vision Transformer
        * https://arxiv.org/abs/1706.03762
    
   - Lab 3: Implementing Vision Transformer & Mini-Project consultation
   
   - Lab 4: Mini-Project (working in groups and consulting)
   
   - Lab 5: (Challenge) Multi-task learning 

### Module 2: Dynamic World and Project

   - Lab 6:  Mini-project presentations 
   
   - Lab 7: (Challenge) Continual Learning  & Project ideas consultation
   
   - Lab 8: (Challenge) Continual Learning cntd.
        * Project proposals are due
   
   - Lab 9: TBD (50% time) + Project consultation

### Module 3: Solutions and Project
 
   - Lab 10: (Solution class) Meta-learning 
        * Project proposals are due

   - Lab 11: (Solution class) Conditional computation
   
   - Lab 12: First project update
   
   - Lab 13: TBD (50% time) + Project consultation
   
   - Lab 14: Second project update

   - Lab 15: Final Project presentation (poster session format)

## Office Hours

I am available immediately after the lab for office hours.

## Requirements

* Completing Machine Learning or Neural Networks course, or **demonstration** of equivalent knowledge

## Lab

* Approximately 50% of our labs will be devoted to working on a project and consulting it throughout the semester. 

* You will be working on the project in groups of 2-3. 

* We will try to use gather.town. Your feedback is essential: we can switch to teams if you prefer. Why gather.town:

    - Pernament whiteboard
    
    - Easy to see where I am during consultation
    
    - Easy to ask question privately
    

## Project and Mini-Project

* Your grade will largely depend on completing a Project and a Mini-Project 

* The Mini-Project will focus on Transfer Learning
    
    * Preferred topic is using GPT-2, Vision Transformer, or CLIP in some context
    
        - See [this list](https://www.reddit.com/r/MachineLearning/comments/ldc6oc/p_list_of_sitesprogramsprojects_that_use_openais/) for inspiration

* The Project will be carried out in groups of 2 to 3 students

    * Preferred topic is reproducing a highly cited or accepted into a prestigious conference paper that addresses any of the challenges
    discussed in this course. See https://reproducibility-challenge.github.io/neurips2019.
    
    * Specific topics for the Project will be announced later, and feel free to suggest your own
    
    * Every two labs devoted to project you will be asked to show your progress and describe your next tasks.


## Attendance

- Attending labs is required (2 abstences are OK, more are of course possible but please reach out with an explanation)

- Attending lectures is optional


## Lab Grading

Your grade will be based on:

- (~20%) Completing a few small exercises (3-4) including reading papers. 

    Exercises have to be submitted by Thursday midnight via email.

- (~20%) Miniproject 1: We will together work on a specific topic and explore few ideas around it that illustrate concepts in Stationary World

- (~60%) Project
    
Specific gradient for Project and Mini-Project will be announced later.

Each week past the deadline for a given homework results in a 25% penalty point penalty.

Your grade will calculates as follows:

* 0-49%: 2

* 50-59%: 3

* 60-69%: 3,5

* 70-79%: 4

* 80-89%: 4,5

* 90-100%: 5

## Final Grade

Final grade will be based on:

- Exam

- Lab Grade

- (Only PhD students) Lecture (PhD students will be required to prepare a lecture)

We will announce details on exam later, but we can already say that an important component will be understanding papers
discussed during the lab.

## Compute

* You will need at least a single GPU. Google's Colab seems to be the best option

  - Paperspace looks interesting but I found it has a very long startup time.
