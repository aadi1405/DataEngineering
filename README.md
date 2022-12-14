# Data Engineering IDS 706 taught by Professor Noah Gift

## Why??

Everything Data Engineering!!

Mostly about my learnings from class IDS 706 @ Duke University! Hoping that this repository will be useful if you're looking to take up this course or are simply interested in Data Engineering!

---

### Week 1 - Discussion


```
Create a life-long learning plan by answering the following questions: **
What skills are you going to learn this quarter, why and how?	
What skills are you going to learn by the end of this year, why and how?
What skills are you going to learn by the end of next year, why and how?
What skills are you going to learn by the end of five years, why and how?
The length of post: max 500 words 
 
```

-In this quarter, few of the things I want to focus on is-
       1) Strengthening Data Structures & Algorithms Concepts
       2) Becoming Proficient in Python and
       3) Diving into the world of Data Engineering (including AWS, SQL, Bash) 
       by using the available resources, exploring the internet and collaborating with others! This will help me with my long-term goals.
       
-By the end of this year, I want to be confident with my Data Engineering skills (including programming, database systems, communication etc.) 
by working on projects and completing certifications. I also want to learn and build my Github profile and create a platform for other students 
to learn along with me (about different courses, concepts, projects etc.). 

-I wish to strengthen the skills learnt in the last quarter of 2022 by working on real-world projects in 2023. I wish to develop Machine Learning
models with everything I learnt through the years especially to help the health-care industry (using health-care data). As a Masters in Engineering 
Management Student, by the end of next year, I also wish to develop my management & technical skills by interning at a company. 
(It would be great to gain experience and put everything learnt to use in an industry alongside others!) 

-The future can be very uncertain but I???m excited to see what it holds! I'm currently interested in Data Science / Data Engineering, it is something 
that excites me and I wish to continue pursuing it in the future. Learning is a continuous process and technology is constantly evolving. 
In five years, I want to be in a place where I am up to date (or at least trying to be!) with the technology around me.

---

### Week 2 - Discussion

```
What are the advantages of knowing both Vim and VSCode?
```
It is always good to try out different tools and editors to understand which one suits your (coding) style the best!

 
-Vim is convenient for making small changes to your file,  allows quick access to files and also is highly scalable. This text editor is also known to be highly configurable which allows efficient programming!
 

-I personally love VS Code due to its user-friendly features like auto-suggestion, auto-indention, easy access to extensions, visual convenience etc. It also allows us to program in different languages and integrate files easily. It is also very convenient when working with large files due to its clean graphical interface and debugging capabilities.


On researching, I found that knowing both Vim and VS Code provides the convenience of not only working with each of the editors individually but also enabling the use of Vim on Visual Studio by using VSVim (kind off like the best of both worlds!) It is also about "for what", "when" and "how" we make use of each of these editors.

---
### Week 3 - Discussion

```
What are the advantages of Microservices?
 ```
	
Troubleshooting and error detection will be more convenient. It allows fault isolation and becomes easier to maintain code.
	
Reduces security risks and increases reliability as the functioning of one component wont affect the functioning of another.
	
Due to its independent nature, it can be easily deployed in different environments. Hence, microservices are also highly reusable. Developers will be able to reuse code and don't have to build projects from scratch.
	
They are scalable and require relatively less resources as they're precisely scaled only to the components that require it. 
	
Microservices are prioritized and  used by businesses today as they are efficient,  help reduce downtime, and allow to segregate different functionalities.
	
Cloud microservices are great as they allow collaboration between people and hence help in parallel computing, so different teams can work in parallel and this makes the development process quicker.

---
### Project 1 

[MOVIE RECOMMENDATION SYSTEM](https://github.com/aadi1405/IDS706_Project1_AJ)

---
### Week 4 - Discussion

FlaskAPI, FastAPI, and Django are all frameworks that are available in python particularly for developing web applications. I gathered some important points about the three frameworks that will help us understand each of these frameworks and decide on which framework to use!
 



**Flask:**
Flask is a small, lightweight framework.
Minimalistic frameworks that is mostly for developing fast websites
Following FastAPI, Flask is pretty fast.
Readable, beginner-friendly and less complex.


**Django:**
Django is a more common, open-source high-level framework.
Full-stack web development framework with large number of packages.
Django is not as fast as FastAPI or Flask.
Well Documented and more scalable.



**FastAPI:**
FastAPI is a new-er and more modern framework (first release was in 2018)
Minimalistic frameworks that is mostly for developing fast websites
In terms of performance, just like the name, FastAPI is fast.
Less debugging time, simple and fast.

Based on the factors above-

We can use Django for creating large scale, more complex scalable web applications. Example - social media applications (Fun fact: Instagram , Youtube and Spotify use Django), huge online market or shopping websites. Flask can be used for static sites or e-commerce site. FastAPI can be used in a situation where speed is a concern and the documentation of FastAPI is still growing (Fun fact: Uber uses FastAPI)

---
### Week 5 - Discussion

What is the difference between Docker and Virtual Machine.
Often Docker containers are confused as Virtual Machines but Docker containers are not Virtual Machines even though they are often compared together.



DOCKER
Generally, virtualizes only the application layer of the OS and uses the kernel of the host
Docker size is generally smaller(KBs/MBs)
Docker containers are faster
Easy to scale-up and duplicate containers, relatively less rescue usage.


VIRTUAL MACHINE
Larger when compared to Docker.
Generally, Virtualizes both the application layer and the Kernel (So, it boots up on its own kernel!)
Slower when compared to Docker, and since they have to start their own kernel.
More Resource Usage



