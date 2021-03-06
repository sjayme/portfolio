---
title: "IoT Exchange"
date: 2018-10-07T13:16:39-07:00
draft: false
---

![tcc starting pic](/portpics/tccportfolio.jpg#center)

**Name:** IoT Exchange <br>
**Company:** The Channel Company <br>
**Role:** UX/UI Designer <br>
**Mentors:** Adelaide Reilly, Rauline Ochs, Mark Petter <br>
**Team members:** *Team Fluent.ly* - Julia Hoang, Victoria Lai, Kyle Mamiit, Chris Pile <br>
**Stack:** React, Node, MySQL, Express, AWS

---

## Overview
For my senior design capstone project I teamed up with four other students to design and develop a working web prototype of a matching system for The Channel Company. This system contributes to the growing IoT solution market by matching Information Technology (IT) and Operational Technology (OT) partners together in order to develop solutions to satisfy end customers.

### The Approach
To tackle such a large task as this it was important to step back for a second and not jump right into designing the system. I needed to understand:


* Who is this system going to be designed for?
* What are the problems they face in the process right now?
* How will this system improve their work?


There are five sections within this case study that outline the approach of this project.


* **[Context:](/iotexchange/#context)** Problem/Goal
* **[Understanding Users:](/iotexchange/#understanding-users)** Company research, Interviews, Personas, Competitive Analysis
* **[Setting the Stage:](/iotexchange/#setting-the-stage)** Requirements, Interaction Flow
* **[Design:](/iotexchange/#design)** Wireframes, Prototypes
* **[Final Thoughts:](/iotexchange/#final-thoughts)** Lessons learned


----------------------------

## Context
### The Problem/Goal
Currently, there exist no company that possesses all the skills to fulfill IoT solutions on their own. Most companies hold expertise in either IT or OT and need to find partners with the skills they are missing in order to successfully create IoT solutions for customers. The current process of finding partners to work with is inefficient and time consuming due to how manual of a process it is. Although a few large companies are starting to combat this large task on their own, other companies turn to The Channel Company for consultation about who they should work with based on their skills and expertise. How will the IoT solutions market grow if companies must jump over multiple hurdles to find someone to work with?

The goal for this project is to design a web system that helps users quickly find partners with the skill sets they are looking for at any time of the day.


### Constraints
As a team we were not sure how to develop this matching system. On one hand, many systems are moving to mobile. On the other hand, we did not think many companies would use a mobile device to find such valuable information on partners. We ultimately chose to design and develop a web application.

Time was also a very large constraint. With only two quarters (about 20 weeks) to work on this project we needed to make sacrifices to the features within the system.

----------------------------

## Understanding Users
### Company Research
Before jumping straight into designing the matching system it was imperative to learn more about The Channel Company and what they do. With a large task like this it was important to understand all the different terminologies used in their field of work to truly understand what needed to be developed. After all, how would I be able to contribute to creating a system for a company if I wasn’t sure what they do? With the use to video tutorials and further explanation from my mentors I was able to understand and answer:

* What are main goals of The Channel Company?
* How do they contribute to the IT channel?
* How can this system improve their work with vendors?

Researching about The Channel Company allowed me to feel even more invested with the project. It eliminated any confusion I had at the beginning of the project. Understanding their values and goals allowed me to design for them as well as for end consumers.


### Interviews
Due to The Channel Company’s connection with vendors we were able to interview four companies aimed to be end users. We spent a week interviewing individuals from companies such as Wachter, KMC Controls, OSTusa, and CISCO. Our team focused on their relationship with The Channel Company, their take on collaborating with other industry partners, and finding holes in the current process of finding partners. After all interviews we were able to understand what types of users would be using this system and their need for the system.

With all these interviews we understood who we were designing for. We found that there are two umbrella types of users to keep in mind when designing:


* **Large vendors (i.e. CISCO, KMC Controls).** Need to quickly identify capabilities of channel partners.
* **Small partners (i.e. Wachter, OSTusa).** Need to be able to trust partners going forward in order to ensure the project does not fall through.

From these interviews we found that the biggest challenge these people face is that:

* There is a lack of trust when trying to partner with other people in this industry. Nobody is ever completely sure they could trust a partner because some people are not completely truthful about their skill sets and this may hinder product launch. They need a trustworthy source that allows for more trust between partners.


We also found how this system would improve current processes:

* **Allow for better partnerships.** Instead of hiring people for a project it is easier to partner with others to complete IoT solutions. IT and OT partners working together allows a lot more projects will be accomplished. It would be a step to eliminating fear between partnerships.
* **Speeded development.** Without having to worry about finding the right partner users will be able to rely and problem solve together quickly.


### Personas
Using what we have found from the user interviews we were also able to create personas and matching scenarios in order to enhance our understanding of the users.

![persona 1](/tcc/persona1.png#center)

“My team has been handling an opportunity with a leading agricultural company for a few weeks. This company wants us to create grid routers that withstands extreme cold weather that allows employees to easily connect with while researching within the fields. My team sent me a Products & Services bill of materials to look over earlier and I was astonished by all of the skills we were missing! We heavily lacked the vertical expertise of agriculture and needed someone to partner up with to fulfill that skill. Luckily I was able to log in quickly to The Channel Company’s (TCC) partner match system and find someone in no time. I entered everything listed on my bill of materials into the system, chose which skills I already had within my company, and then picked the skills I was looking for. I specified that I was looking for a match within a 50 mile radius of Irvine and clicked next. Before I knew it, three matches came up. The first hit was easily distinguishable from the other two because we had successfully done business with them before. I matched with them again and we were in contact just a few hours later.” 
--- **Duane Warner on using The Channel Company’s partner system (2018)**

![persona 2](/tcc/persona2.png#center)

“My company just recently launched in Kansas City and specializes in operational technology such as cabling. We asked The Channel Company to help us gain exposure in our recent partnership. They have done a few marketing events for us but we have not heard back from any vendors. It is hard to keep paying them when we are barely just making it as a company. Upon hearing about the partner matching system, we gave it a go in hopes for a partnership. We felt like we couldn’t just wait for a vendor to have an opportunity when we had some ideas of our own. Because we have already partnered with The Channel Company, all of our data was already available upon signing up. It was pretty simple learning how to use the system on my desktop since I did live in a tech savvy area during my college years. After I used the partner matching system, I found a company that specializes in all of the IT skills that we lack within a 50 mile radius. I think this is finally our opportunity to grow and get the exposure we have been waiting for.”
--- **Lisa Walters on using The Channel Company’s partner system (2018)**

![persona 3](/tcc/persona3.png#center)

“As someone who has been overseeing IoT operations for a while now, I have seen how beneficial it is to have all the skills required to build an IoT solution in-house. With every project our company is consulted for, I encourage my team to work closely with the corresponding OT partner so they can observe and pick up on the skills needed to implement OT aspects of IoT solutions. While we do not have a mastery of all skill sets within our organization yet, our team has an understanding of what it takes to develop a successful IoT solution. Because of this, our company is beginning to look into the development of our own IoT solution and would like to be paired with appropriate partners that will help us achieve this. We know the skills that our team has and the skills that are lacking, all we need is a way to identify the right partners for our project. We reached out to The Channel Company for help because we are aware that they are basically the primary facilitators of the IT/OT channel. They opted us into a matching service they developed to help partners and vendors find partners that complete their IoT solution skill requirements. We went ahead and conducted a search and was quickly provided with matches that satisfied the skills we needed. The matches were interesting because they indicated vendor nominations, which helped our team identify partners who have a successful track record with IoT partnerships.”
--- **Mike Simon on using The Channel Company’s partner system (2018)**



These personas gave me a better understanding of the types of people we are designing for and what they need. It also provided my team with a shared understanding of the people we are designing for and the goals we needed to keep in mind to cater to them.


### Competitive Analysis
As part of the UI team, we also took a look at other matching systems that companies provide. We looked at three competitors in particular, Cisco, Microsoft, and Catchafire to get an idea of what is expected in a system like this.

![ciscoCA](/tcc/tcccomp1.png#center)

![microCA](/tcc/tcccomp2.png#center)

![catchaCA](/tcc/tcccomp3.png#center)

Reviewing the small pool of competitors gave us design inspiration. We noticed different strengths and weaknesses from each competitor and were able to brainstorm what would best fit with the system we needed to implement.

----------------------------

## Setting the Stage
### Requirements
As a team we started to brainstorm what the system required. Below is a use case diagram of the functional requirements we decided on. 

![tcc reqs](/tcc/tccreqs.png#center)

Some key features include:

+ **Sign Up:** Users must be able to sign up as either a vendor or a partner. Here they specify their skill sets.
+ **General match:** Users need the ability to search for a partner with certain skill sets. They are also able to specify what location to narrow down the results.
+ **View match results/history/in-progress:** These three are connected together involving the information shown to the user after the initial match. It provides the user feedback and allows them to feel progress when using the system.
+ **Dashboard:** Team Fluent.ly decided that all these features would be neatly placed into a dashboard for quick access.

### Interaction Flow
![tcc interaction](/tcc/tccinteraction.png#center)

We aimed to make the interaction flow as simple as possible. Everything is connected to the central dashboard which allows for users to easily access all the features of the system.

----------------------------

## Design
### Wireframes

Below are the wireframes for the most important features of the system.

![tcc wireframes](/tcc/tccwireframes.jpg#center)

For the interface we wanted to create a clean and simple design to order to lessen any confusion users potentially might come across. We aimed to create interfaces that were intuitive enough for anyone to use. Arguably the most important page, the start a match page, features checkboxes to click on that represent each skill they are looking for. We decided on checkboxes because we thought it was quick and efficient while still being easy to understand.

### Prototypes

Below are screenshots of our system. Due to time restrictions, The Channel Company wanted us to perfect the backend of the system rather than the frontend. We dedicated most of our time getting the database finished and fetching the right data. Unfortunately, there were ideas that we were not able to implement because of this such as Geo Location for finding a match and the match history.

![tcc login](/tcc/login.png#center)

![tcc dash](/tcc/dashboard.png#center)

![tcc start match](/tcc/startmatch.png#center)

![tcc found match](/tcc/foundmatches.png#center)

----------------------------

## Final Thoughts
### What's Next
The next stage for this system is to get the look and feel of The Channel Company integrated within it. At the end of the school quarter, the system looks very simple because of the time constraints and the shift in our focus when working on it. Implementing the features that we were not able to touch on within our time on this project will also be done in the future. Integrating The Channel Company's branding and finishing features will push the system in the right direction and closer to getting it online for users to try. 

### Lessons Learned
This project was the biggest project of my undergraduate career at UCI. I was able to enhance my teamwork and communication skills in order to design a working prototype for a success company filled with knowledgeable people. With weekly meetings with The Channel Company as well as Team Fluent.ly I was able to get accustomed to an agile workflow and high intensity work loads.