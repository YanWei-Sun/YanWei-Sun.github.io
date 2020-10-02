---
title: Research
date: 2020-10
type: "Research"
---

**_'Create something most useful or most beautiful'._**   This page presents my research experience (**up to Oct 2020**)

---
# Text Mining in Education

**Mentor: *Prof. [Farrokh Mistree](http://http://scholar.google.com/citations?user=l1N0Nj0AAAAJ&hl=en)* & *Prof. [Janet K. Allen](http://https://scholar.google.com/citations?user=oJNeHV0AAAAJ&hl=en)***    &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; **July,2020 - Oct 2020**

In education, it's imperative for instructors to figure out to which degree does students' learning matches the target learning. We have roughly ten thousands data cases,collected from the course AME4163: Principle of Engineering Design (POED) at University of Oklahoma (OU). These data could reflecte what the students focus (Take Away data) in the course and the target lerning (POED data) of the course. However, it's impossible to mannualy analyze these data and provide insights from the data for the instructor to modify the course. 


Latent Dirichlet Allocation (LDA) is a generative, probabilistic model for *topics modeling*. In our framework, we use LDA to extract each Take Away document's topic (the distributio of topics and each topic is a distribution of words). However, our POED doucment are very short, which LDA is not suitable for. Thus, we utilize TF-IDF each POED document's key words, and identify each POED's weight in each topic by calcauling cosine similarity between the vector of each POED and vector of each topic.

Our result shows that except assignment 4, students performed well in both sections (different sections mean different instructors). After diving into the courses, we find that the instructive book of the book has a wrong target learning content, which misleads the students. 
{% img /images/Text_Mining/section1.png %}   {% img /images/Text_Mining/sectionII.png %}   

We also find that although two instructors adopted the same courses slide and the same instructive book, students in assignment 3 had a quite different performance between section 1 and section 2. Then, we use Scattertext, which is powerful python library to visualize the difference between documents, to show the difference between these two sections. 
{% img /images/Text_Mining/A3_Scattertext.PNG %}  

----
# Decision-Making in Crowdsourcing

**Jan,2020 - now**

In this project, we focused on **crowdsourcing**, which is supervised by Prof. [Zhijun Ming](https://scholar.google.com/citations?user=x1ulAm4AAAAJ&hl=en)

Crowdsourcing has been widely used as a way to facilitate open innovation where ideas from outside an orgranization are sought to supplement internal activities. For example, instead of hiring a research team to develop a better collaborative filtering algorithm, Netflix issued the 'Netflix challenge' offering a million doallors to the team that develops an algorithm that beats the Netflix algorithm by 10%. 

Nearly all of the current frameworks of crowsourcing is **_Once submitted_**, which means the particpants just need to sumbit their wokrs once before the  fineal deadline. Also, most of the researches about crowdsourcing are still based on the **_hypothesis of rational man_**, which is the foundation of _game theory_. However, what if there exists multipe deadlines during the game? What if 
 the players are not rational or partly rational? 

In view of the above problems, on one hand, we introduce the **_Mid-term feedback_** into the framework of crowsourcing; on the other hand, we try to quantify **_the level of irration_** mainly based on the [_Generalize Recursive Reasoning_](http://arxiv.org/abs/1901.09216), which I think is a milestone.  **_Mid-term feedback_** means the sponsor will set up mutiple deadlines during the game and the players need to submit their works before every deadline, even though the works unfinished;then the sponsor will public the ranking of works. By this, the players could gain more information about their competitors and based on these information to decide the next movement.

----
# Robotics

**June,2019-Now**

In this project, we have 5 members and I'm the teamleader. Our mentors are  Prof.[Lingjia Kong](http://me-english.bit.edu.cn/people/faculty/k/125069.htm) and  Prof.[Jieliang Zhao](http://scholar.google.com/citations).

With the aging of the social population increasing, the old people's need 
for companionship and care is more and more prominent; after market research, it is 
found that there is no companion robot for the elderly in the market; based on this, a 
**_smart companion robot dog_** was developed in this project. Through the functional
design of the mechanical dog, the purpose of accompanying the elderly, caring for the 
elderly, and better alleviating the emotional problems of the elderly can be achieved.

For this project, I'm responsible for the **_leg movement_**. Specically, I adopted the **cam structure** to realize the movement of the mechanical dog,which can make the robot dog touch the three legs at the same time when walking, and the trajectory of the foot end is an ellipse plus a straight line.which will increase the stability when walking.

**Now we have two patents under application about this mechanical dog (I as the first inventor)**
