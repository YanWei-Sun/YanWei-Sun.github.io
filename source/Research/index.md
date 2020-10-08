---
title: Research
date: 2020-10
type: "Research"
---

**_'Create something most useful or most beautiful'._**   This page presents my research experience (**up to Oct 2020**)

---
# Text Mining in Education

**Mentor: *Prof. [Farrokh Mistree](http://http://scholar.google.com/citations?user=l1N0Nj0AAAAJ&hl=en)* & *Prof. [Janet K. Allen](http://https://scholar.google.com/citations?user=oJNeHV0AAAAJ&hl=en)***     &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; **July,2020 - Oct 2020**

In education, it's imperative for instructors to figure out to which degree does students' learning matches the target learning. We have roughly ten thousands data cases,collected from the course AME4163: Principle of Engineering Design (POED) at University of Oklahoma (OU). These data could reflecte what the students focus (Take Away data) in the course and the target lerning (POED data) of the course. However, it's impossible to mannualy analyze these data and provide insights from the data for the instructor to modify the course. To fill in this gap, we devise **a framework to automatically connect what students had learned to what they should learn, mainly based on Latent Dirichlet Allocation (LDA) and Term Frequency–Inverse Document Frequency (TF-IDF)**.


Latent Dirichlet Allocation (LDA) is a generative, probabilistic model for *topics modeling*. In our framework, we use LDA to extract each Take Away document's topic (the distributio of topics and each topic is a distribution of words). However, our POED doucment are very short, which LDA is not suitable for. Thus, we utilize TF-IDF each POED document's key words, and identify each POED's weight in each topic by calcauling cosine similarity between the vector of each POED and vector of each topic.

Our result shows that except assignment 4, students performed well in both sections (different sections mean different instructors). After diving into the courses, we find that the instructive book of the book has a wrong target learning content, which misleads the students. 
{% img /images/Text_Mining/section1.png %}   {% img /images/Text_Mining/sectionII.png %}   

We also find that although two instructors adopted the same courses slide and the same instructive book, students in assignment 3 had a quite different performance between section 1 and section 2. Then, we use Scattertext, which is powerful python library to visualize the difference between documents, to show the difference between these two sections. 
{% img /images/Text_Mining/A3_Scattertext.PNG %}  

----
# Game Theory in Crowdsourcing

**Mentor: *Prof. [Zhijun Ming](https://scholar.google.com/citations?user=x1ulAm4AAAAJ&hl=en))***     &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; **Jan,2020 - Oct 2020**


Crowdsourcing has been widely used as a way to facilitate open innovation where ideas from outside an orgranization are sought to supplement internal activities. 
Nearly all of the current theoritical frameworks of crowsourcing is one stage, where participants just need to sumbit their works one time before the fineal deadline. However, some crowdsourcing platforms has adopted two-stages contests. In order to fill in the gap from mathetical perspective, **we have the following questions to address**:

- **Whether two-stages crowdsourcing contest is better than one stage in terms of sponsor's pay-off**
- **For sponsor how to set up the parameters(four as following) to maxmize his/her pay-off**
  - **the ratio of total funding in stage-1(α) and stage-2 (1 − α)**
  - **the duration of stage-1(T1) and stage-2(T2). (T1 + T2 = T)**
  - **the rate of exclusion at the end of stage-1 (1 − β)**

We use game theory to model participants behaviors and build a theoritical 2-stages crowdsourcing contests model, which belongs to non-linear programming.

Our result shows that based on our assumptions, such as the rational people, the 2-stages crowdsourcing will not worse than 1-stage. 
{% img /images/Crowdsourcing/n_comparison.png %}   {% img /images/Crowdsourcing/PI_comparison.png %} 

Also, given the total prize of the contest, the duration and the number of participants, we could provide the optimal parameters. One example is shown as following:
{% img /images/Crowdsourcing/example.png %} 

----
# Robotic Design

**Mentor: *Prof. [Jieliang Zhao](http://scholar.google.com/citations).* & *Prof. [Lingjia Kong](http://me-english.bit.edu.cn/people/faculty/k/125069.htm)***     &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; **June,2020 - Oct 2020**


With the aging of the social population increasing, the old people's need for companionship and care is more and more prominent; after market research, it is found that there is no companion robot for the elderly in the market; based on this, a **_smart companion robot dog_** was developed in this project. Through the functional design of the mechanical dog, the purpose of accompanying the elderly, caring for the elderly, and better alleviating the emotional problems of the elderly can be achieved.
{% img /images/dog.png %} 

For this project, I'm responsible for the **_leg movement_**. Specically, I adopted the **cam structure** to realize the movement of the mechanical dog,which can make the robot dog touch the three legs at the same time when walking, and the trajectory of the foot end is an ellipse plus a straight line.which will increase the stability when walking.
{% img /images/leg.png %} 

**Now we have two patents under application about this mechanical dog (I as the first inventor)**
