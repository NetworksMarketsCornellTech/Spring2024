---
layout: page
title: Syllabus
permalink: /syllabus/
---
# ORIE 5355/INFO 5370: Applied Data Science - Decision-making beyond Prediction
- Instructor: Prof. Nikhil Garg (he/him), ngarg@cornell.edu
- TA: Zhi Liu, zl724@cornell.edu; and Gabriel Agostini, gs665@cornell.edu
- Credits: 3 hours, Letter Grade
- Lecture Timings: Mondays/Wednesdays, 2:55PM - 4:10PM [In person, Bloomberg 131]
- Instructor office hours: Wednesdays, 4:10 - 5pm [Bloomberg 454 + zoom]
- TA office hours: Monday 1:30 - 2:30pm, Friday 2 - 3pm. [Check calendar for location]

<b>Important links</b>
 - [Course website]({{"/" | prepend: site.baseurl }})
 - [Canvas](https://canvas.cornell.edu/courses/57049)
 - [Ed Discussion](https://edstem.org/us/courses/41491/) -- Primary communication tool
 - [Calendar](https://calendar.google.com/calendar/u/0?cid=NGw4b2Iwb2NzZmF0NDl0bDI3MG9kcm91ZW9AZ3JvdXAuY2FsZW5kYXIuZ29vZ2xlLmNvbQ) -- Class google calendar with lectures, OHs
 - [Gradescope](https://www.gradescope.com/courses/557420) -- Place to turn in all assignments
 - [YouTube](https://www.youtube.com/playlist?list=PLPjsPBAj-5PWX8dWDcqYfMvEuh7DWuBEJ) -- Lecture recordings from 2021. 

# Course Description
This course considers the data science challenges beyond training an accurate predictive model, especially for systems about people (data of behavior), and for people (deployed models to influence behavior). Whether for online marketplaces, transportation, governmental, or urban systems, effective data science in such settings requires dealing with user incentives and strategic behavior, networked and decentralized decision-making, and privacy and ethics concerns.
This course is about all the ways introductory statistics/data science/machine learning fails when deployed in such systems, and how to nonetheless build effective systems.

This course covers topics necessary to effectively analyze data and deploy decision-making models in such systems, providing both conceptual frameworks and hands-on data science practice. Core topics include every step of the data collection, analysis, experimentation, and model deployment pipeline. A running theme will be the practice of designing systems with privacy, fairness, ethics, and transparency in mind. We will motivate challenges and demonstrate solutions from across domains, including recommendations, matching, pricing, scheduling, and ratings and feedback systems. A guided data science project will connect concepts to practice.

This course is complementary to the other data science, machine learning, and operations courses at Cornell Tech. It is accessible to students who have not taken those courses yet, but also interesting and novel to those who have. Some topics (such as pricing, recommendations, and experimentation) might overlap with those covered in other courses, but the focus here is on practice and on the particular challenges of socio-technical systems -- and the overlap is minimal. The course content and assessment is a mix of conceptual, theoretical, and programming-based.

Consult [here](https://docs.google.com/document/d/16TWYj7ojFrDB47qc_SUa7xmX-OWtQiibpWVaN_jCSr0) for a guide to how this course relates to other data science courses at Cornell Tech.
Student Outcomes: Students will be able to articulate common challenges in data science about and for people, and design, develop, and deploy data science models that effectively deal with such challenges.

## About the instructor
Nikhil is an assistant professor of Operations Research and Information Engineering at Cornell Tech, whose research is at the intersection of computer science, economics, and operations -- on the application of algorithms, data science, and mechanism design to the study of democracy, markets, and societal systems at large. Things he’s worked on include 311 reporting systems, surge pricing, rating systems, how to vote on budgets, gerrymandering, stereotypes in word embeddings, and political polarization on Twitter. Outside of academia, Nikhil has been a data scientist at Uber, collaborated with Upwork and other freelancing marketplaces, and most recently led campaign data science at PredictWise during the 2020 US election cycle.

## Prerequisites and Preparation summary
The homeworks will require use of Python, and the course assumes basic knowledge; in particular, from the beginning we assume that you are able to (or can pick up on your own) load and manipulate datasets in Python using Pandas and Numpy and calculate summary statistics such as weighted means. Please refer to the first homework assignment as a gauge for the level of Python we expect. We also assume some knowledge of statistics or data science: that you are familiar with introductory statistics concepts such as means, bias, variance, distributions, and linear algebra concepts such as matrix multiplication, vector norms, and dot products.

### Corequisites
Applied Machine Learning or Urban Data, or equivalent, is required as either a prerequisite or a corequisite. In particular, we will assume after the initial part of the course that students have been taught the broad ML/data science modeling fundamentals that those courses teach, including, for example, how to implement various models in Python notebooks and to evaluate their performance.

## Class and Laboratory Schedule:
Lectures: 3 hrs/wk

Recitations: None required.  Optional office hours with TAs and instructor

## Textbook(s) and/or Other Required Materials:
None required to purchase. All readings will be distributed throughout the semester.
All software used will also be open source/freely available.

## Course communication
Course communication will primarily be over Ed Discussion, office hours, and email.
 - <b>Ed Discussion</b>: First resource for any question, whether regarding technical content or logistics. Please make your question visible to everyone, so that others may answer or benefit from your question. Instructors will aim to respond to questions in a 48-72 hour period, except for those of an urgent nature (e.g., typos on homeworks or lecture notes, clarifying course logistics, etc.).  Among other things this means you should not wait until the last few days before an assignment is due to message us; we may not respond in time. You are encouraged to answer questions from other students, especially during the instructor “waiting period.” 
 - <b>Office hours</b>: You are strongly encouraged to come to office hours for any reason. Office hours are the best way to ask in-depth technical questions, whether directly related to the course content or just things you’re interested in. TA office hours will often cover the homework questions in depth.
 - <b>Email</b>: Only for private questions and concerns, such as requests for accommodations or regrade requests. Please include “[ORIE5355]” in the subject line of any email. Technical questions will not be answered over email -- please use Ed Discussion.

Please follow [these norms]({{"/class_norms/" | prepend: site.baseurl }}) in all communications with the instructors and other students.

## Typical course topics covered
- Data collection (~3 weeks)
    - Data constructs, surveys, ratings, polling, and implicit data exhausts
    - Challenges and biases: censoring, strategic reporting, social desirability, ratings inflation, privacy, etc
    - Technical solutions to challenges: stratification, weighting, post-processing
    - Non-technical solutions and case studies
- Recommendations (~2 weeks)
    - Collaborative filtering and personalized recommendations; individual vs demographic based recommendations
    - Recommendations in practice: Capacity constraints, matching, 2-sided fairness, and other challenges (such as limited + missing data)
- Algorithmic pricing (~2-3 weeks)
    - Basics of posted price mechanisms, algorithmic pricing
    - Personalized and dynamic pricing in practice (online marketplaces, supply/labor side wages, and roadway congestion pricing)
    - Fairness, ethics, and limitations
- Experimentation (~2-3 weeks)
    - A/B testing basics
    - Experimentation in practice: networks, interference, clustering, experimentation over time, switchbacks, 2-sided experimentation, trade-offs across experiments
    - Ethics and communication of experiments
    - Introduction to causal inference without experiments
- Miscellaneous (~2-3 weeks): Exact topics based on student interest
    - Algorithmic explainability and transparency
    - Performance drift, strategic reactions to your model, Data feedback loops
    - Human-in-the-loop machine learning
    - Fairness audits and interventions
    - Differential privacy


## Assignments, Exams and Projects
 - <b>Homework: 50%</b>. Four homeworks. Each HW is an equal part of the homework grade. Lowest score replaced by project grade.
 - <b>Final project: 30%</b>. Programming-based project coding an algorithmic agent that does recommendation and/or pricing. 
 - <b>Biweekly quizzes: 10%</b>. 4-6 biweekly quizzes. Lowest score dropped.
 - <b>Participation: 10%</b>. Attend online/in-person class and have meaningful participation in the class community. Complete the ccasional class survey, as well as the final official course evaluation.

 Detailed HW assessment is available here: [https://orie5355.github.io/Fall_2023/assignments/](https://orie5355.github.io/Fall_2023/assignments/), and project assessment is available here: [https://orie5355.github.io/Fall_2023/project/](https://orie5355.github.io/Fall_2023/project/).  

 Tentative assignment deadlines (these dates are unlikely to be earlier, but may be later). Quizzes will either be in class or posted online on the stated date:
- HW 1 -- 9/12
- Quiz 1 -- 9/13
- HW 2 -- 9/26
- Quiz 2 -- 9/27
- HW 3 -- 10/17
- Quiz 3 -- 10/18
- Hw 4 -- 10/31
- Quiz 4 -- 11/1
- Quiz 5 -- 11/15
- Project Part 1 -- 11/21
- Project Part 2 code -- 12/3
- Project report -- 12/12

**Basis of grade determination**

Letter grading. Grades will be at least as generous as the following, with A+ given at the instructor's discretion.

 - A: 94-100
 - A-: 90-93
 - B+: 85-89
 - B: 80-84
 - C: 70-80
 - F: < 70

## Assessment
Primary assessment is based on 4 homeworks, about 4-6 quizzes, and a project. We will replace your lowest homework grade with your project grade (if it is higher), so that your composite homework grade will be based on your top three homework scores and final project score, evenly weighted. The biweekly quizzes will be short, usually given the week homework is due. They should be straightforward given lecture attendance and homework completion. Your lowest quiz grade will be dropped.

You will be allowed four total late days during the semester for homeworks.  These late days allow you to turn in homework up to 24 hours late, with no penalty; you may also use all the late days on a single homework assignment (allowing you to turn it in up to 96 hours late), but that will leave you with no late days for other homeworks. When submitting an assignment late, please mark at the top how many late days are used for this assignment and how many you have used before, if any. Late days cannot be used for quizzes or the project -- only homework.


### Regrade, late assignments, and extensions policy
[Research](https://www.nber.org/system/files/working_papers/w26703/w26703.pdf) has shown that regrade requests lead to disparities due to differences in who is comfortable asking for regrades. Thus, regrade requests will only be accepted for clear, unambiguous errors in grading, such as when an assignment (or part of it) is marked missing when it was submitted on time in the manner instructed. Unambiguous errors on our part also include marking wrong an answer that is completely correct (code works, it's the right thing to do, gets the right answer). However, it does not include judgement calls, such as whether a "right enough" code deserved 1 pt or 2 pts. In the case of grading errors, however, we encourage you to come forward -- please email the TA and instructor as soon as possible and submit a regrade request on gradescope, within one week of receiving the incorrect grade. For the same reason, we will not accept requests for extensions on assignments besides the late days policy above. We are hoping that between dropping the lowest scoring homework and quiz and the late days policy, you will have enough flexibility to accommodate your scheduling needs during the semester -- without inducing disparities due to differences in who is comfortable asking for regrades and extensions.

## Covid and attendance policy
The course will follow Cornell and Cornell Tech Covid-19 guidelines. [https://tech.cornell.edu/coronavirus/health-safety/](https://tech.cornell.edu/coronavirus/health-safety/) will be the most current place for students to receive guidance about how to proceed if feeling ill. Bottom line: don't attend if you're feeling ill, and we'll figure it out from there. Otherwise, regular attendance is expected in class and grading will partially be based on class participation. Live remote attendance is not an option.

## Academic Integrity
Each student in this course is expected to abide by the Cornell University Code of Academic Integrity.  Any work submitted by a student in this course for academic credit will be the student's own work. The policy can be found on the university’s website here: https://theuniversityfaculty.cornell.edu/academic-integrity/.

You are encouraged to study together and to discuss information and concepts covered in lecture and the sections with other students. You can give "consulting" help to or receive "consulting" help from such students for homeworks and the class project. Except in the case of group homeworks or projects, this permissible cooperation should never involve one student having possession of a copy of all or part of work done by someone else. For group assignments, no group should have in their possession work done by another group. On the top of each assignment, please list everyone with whom you discussed the assignment. Class quizzes must be completed wholly independently, with no help of any kind between students.

Should copying occur, both the student(s) who copied work from another student(s) and the student(s) who gave material to be copied will both automatically receive a zero for the assignment. Penalty for violation of this Code can also be extended to include failure of the course and University disciplinary action.

**ChatGPT, Github Copilot, and LLM policy**. Students are _not allowed_ to use such tools to answer the _conceptual/qualitative_ questions on homeworks. Students are _discouraged_ from using it for the programming assignments, but may use it _with attribution_ -- the homeworks are meant to help you understand the ideas in lecture. We reserve the right to change this policy during the semester.  

## Students with Disabilities
Your access to this course is important. Please give me your Student Disability Services (SDS) accommodation letter early in the semester so that we have adequate time to arrange your approved academic accommodations. If you need an immediate accommodation for equal access, please speak with me after class or send an email message to me and/or SDS at sds_cu@cornell.edu. If the need arises for additional accommodations during the semester, please contact SDS. You may also feel free to speak with Student Services at Cornell Tech who will connect you with the university SDS office.

## Religious Observances
Cornell University is committed to supporting students who wish to practice their religious beliefs. Students are advised to discuss religious absences with their instructors well in advance of the religious holiday so that arrangements for making up work can be resolved before the absence.

## Cornell Tech Cares
The Cornell Tech community is a diverse and vibrant group of students, faculty, and staff.  We take our responsibility to look out for one another seriously. As members of this community, your openness and proactive communication will allow us all to better care for students and respond to their needs, whether they be interpersonal or academic. Please help us continue to build and strengthen our community by reaching out if you are having an issue or are concerned about a fellow student. Contact studentwellness@tech.cornell.edu with concerns and we will make sure to care for one another.  In the event of an emergency, please call 911 and Cornell Tech Safety & Security at 646-971-3611 (This number is also located on the back of your Cornell ID), when safe to do so. The following link also has resources available to Cornell Tech students:
https://studentaffairs.tech.cornell.edu/health-wellness/nyc-health-resources/.
