# CS & Stats Seminar Course 


- **Instructor:** Sarah Brown
- **Meeting Time:** Fridays at 3pm in Tyler 055

## Course Description

This 1-credit course offers students a unique opportunity to engage with renowned experts and visionary leaders in Computer Science and Statistics. Through a captivating series of talks and presentations, participants will gain firsthand insights into cutting-edge research, emerging trends, and practical applications within these disciplines. 

This course is designed to be equivalent to approximately 3 hours of work per week. In addition to attending seminars (1.5 hours per week), students are expected to prepare for seminars (approximately half an hour per week), and reflect after each seminar (approximately 1 hour per week), which will deepen their understanding of the topics covered. Attendance at talks, active participation, and submission of assignments are compulsory for all students.

## Course Objectives

Upon completion of this course, students should be able to:

- Gain exposure to top experts in Computer Science and Statistics.
- Explore cutting-edge research, industry applications, and innovative methodologies.
- Foster networking and collaboration among students, faculty, and industry professionals.
- Envision the future of these fields.
- Engage in critical thinking and in-depth discussions about emerging technologies and their societal impacts.


## Grading 



This course is graded on a Satisfactory/Unsatisfactory basis. 

To pass the course students must earn:
- 10 present or active seminar attendance ratings
- 12 atttempted or complete with at least 10 complete ratings on preparation assignments (basic preparation should take about 30 minutes, advanced about an hour)
- 24 total units of reflection activities(one unit should be about 30 minutes of work). 



:::::{attention}
You can add up to 24 units in *any* combination that you want. Choose what works best for you!
::::::::
[^indev]: this number may change

### Seminar Attendance

You will receive ratings of absent,  present,  active or (rarely) excused for each seminar. Most reasons for being absent will still count as an absence, using one of the two allowed absences.  Only extreme cases will result in excused absences that change the grade calculation.  

Active ratings count as one unit of reflection.


### Preparation Assignment 

You need to prepare for the seminar each week. 

You can choose either of two options for your preparation:

- basic: counts as preparation only
- advanced: counts as preparation, and if well done, can count as a reflection unit

(basic)=
#### Basic Prep


1. Read the abstract and speaker bio
1. Spend 5-10 minutes getting a sense of the speaker's research area and looking up key jargon in the abstract if applicable

Submit answers to the questions, using this template

::::{literalinclude} prepare/basic.md
::::::

(advanced)=
#### Advanced Preparation

Basic prep plus read 1-3 papers by the author to get a more detailed understanding of what to expect. Include a short evaluation of the paper(s) read to prepare 

Submit using the template:

::::{literalinclude} prepare/advanced.md
::::::


### Reflection Activites

You can complete any combination of the following, including repeating the same assignment for different speakers to reach the number of required reflections. 

Seminar Specific Reflections: 
- [Exit ticket](#exit): 1 unit, evaluated as complete or not
- [Deep reflection](#deep)[^revopt] : up to 6 units


Integrative Reflecions (each worth up to 12 units, require integrating ideas from multiple seminars): 
- Develop a [talk schema](#schema) [^iterative] 
- Write a [guide](#guide) for future students understanding talks outside their area [^iterative]
- Develop a personal [tip sheet](#tips) for preparing talks based on what you saw in seminar talks[^iterative]

Alternative Reflections that you propose. 


All of these will be evaluated for depth of thinking and use of relevant examples from the seminar this semester.  

[^iterative]: Revisions are expected for these assignments. Start Early to have time to iterate


[^revopt]: revisions may be required to earn full number of units. Submit early enough to earn the full credit. 

(exit)=
#### Exit Ticket

Answer the short questions with a few statements, these can be bullets
::::::{literalinclude} reflection/exit.md
::::::::

(deep)=
#### Deep Reflection

This should be more complete thoughts. This should be complete sentences and may require some revision.  You will be able to revise submissions as long as they are submitted with enough time. 

::::::{literalinclude} reflection/deep.md
::::::::




(schema)=
#### Talk Schema


Write out how you organize talks conceptually and use it to categorize the talks this semester.  You need to define the labels or axes you use. 

:::::{tip}
**You should start this early**, ideally by February 20 and get feedback. You can request a review, even while it is a draft PR.  This wy you can find out if you are on track or if parts of your work are unclear. Then you'll have time to earn the full 12 units for this. 
::::::::

Questions to think about: 
- How do you define the categories you use in the preparation assignments?
- How have seminars been similar or different?
- How do your expectations of talks vary?

Submit: a single markown file with your schema and labeling of talks.  

::::{tip}
You might use a [mermaid quadrant chart](https://mermaid.ai/open-source/syntax/quadrantChart.html) or other type of visual to categorize the talks. 
:::::::

(guide)=
#### Seminar Guide 

Write a guide for future students on how to understand talks outside their area. It needs to use examples from your experience at seminars. 


Questions to consider in developing it: 
- What strategies have you tried that worked?
- How might you turn things that you struggled with into better advice?
- What do you wish you knew before the semester?


Submit: your guide as a single markown file on its own branch. 

::::{tip}
Submit this by April 1 to ensure you have time to get feedback and iterate
::::::

::::::{note} Option
You can contribute your guide directly to this website repository to make it directly usable by other students. For syntax, use [myst markdown](https://mystmd.org/guide). 
:::::::

(tips)=
#### Talk Preparation Tips

Write a personal tip sheet for yourself for preparing talks based on what you saw in seminar talks. This needs to identify which seminar(s) you learned and garnered the tips from. 


Questions to consider in developing it: 
- What aspects of talks helped you understand better?
- What things detracted from your ability to understand?
- What strategies for explaining ideas verbally helped? what distracted?
- What about the slides was helpful or not? 


Submit: your guide as a single markown file on its own branch. 
::::{tip}
Submit this by April 1 to ensure you have time to get feedback and iterate
::::::

## Work submissions

All work will be submitted to your personal seminar-reflection repository on github. You need to "accept the assignment" from github one time. 

For each assignment you must make a PR with the work and request a review from `@brownsarahm`. 

### Seminar Specifc Assignment Help
For seminar-specific assignments[^semspec] there is a helper action, that you can [run manually](https://docs.github.com/en/actions/how-tos/manage-workflow-runs/manually-run-a-workflow#running-a-workflow).  There is a link to the action page to run it in your repo's readme.  You can also run the action from a terminal in the repo directory: 
```
gh workflow run initialize-assignment.yml
```

:::::{attention}
the action makes a *draft* PR, click "ready for review" once you have filled it in
::::::::

You can work fully offline too: 
- create a branch like `<type>-YYYY-MM-DD` where type is one of prepare or reflect and date is the date **of the seminar** relevant
- install the [utils]()
- `csssem gettemplatefile` and follow the prompts to get the template file created
- fill in the file
- commit, push, and open a PR. 




[^semspec]: seminar specific assignments are [](#basic), [](#advanced), [](#exit), and  [](#deep)

### Other Assignments

Other assignment, you can name the branch and file anything that is related to the content of the work. 

## Announcements

- For updates to this site, watch to the repo (for only major updates, select releases)
- Seminar announcements (abstracts/bios) will be sent to the CSC-STA grad student list serve


## Academic Integrity Policy & AI Use 


All work must reflect your own understanding. A single sumbmission with plagiarized or falsified information will result in an a grade of U for the semester. The student is responsible for all of the work submitted, errors introduced by, for example, use of AI will also result in a grade of U.  

You may appeal by meeting with the instructor. 

## University Policy

### **Viral Illness Precautions Statement** 

The University is committed to delivering its educational mission while protecting the health and safety of our community. Students who are experiencing symptoms of viral illness should NOT go to class/work. The [Centers for Disease Control and Prevention (CDC)](https://www.cdc.gov/respiratory-viruses/guidance/index.html) recommends that all people who are experiencing viral illness should stay home and away from others until symptoms improve and they are fever free (without medications) for 24 hours. They should take added precautions for the next 5 days. 

### **Excused Absences** 

Absences due to serious illness or traumatic loss, religious observances, military service, or participation in a university-sanctioned event are considered excused absences. Students are responsible for work missed during an excused absence but will not be penalized by grading or assignment/exam make-up policies. Students should notify faculty in advance of absences due to religious observance or university-sanctioned events, and as soon as possible for other absences. [See University Manual sections 8.51.11-8.51.16](https://web.uri.edu/manual/chapter-8/chapter-8-4/) for details.

### **Anti-Bias Syllabus Statement** 

We respect the rights and dignity of each individual and group. We reject prejudice and intolerance, and we work to understand differences. We believe that equity and inclusion are critical components for campus community members to thrive. If you are a target or a witness of a bias incident, you are encouraged to submit a report to the URI Bias Resource Team at [www.uri.edu/brt](http://www.uri.edu/brt). There you will also find people and resources to help.

### **Disability, Access, and Inclusion Services for Students Statement** 

Your access in this course is important. Please send me your Disability, Access, and Inclusion (DAI) accommodation letter early in the semester so that we have adequate time to discuss and arrange your approved academic accommodations. If you have not yet established services through DAI, please contact them to engage in a confidential conversation about the process for requesting reasonable accommodations in the classroom. DAI can be reached by calling: 401-874-2098, visiting: [web.uri.edu/disability](http://web.uri.edu/disability), or emailing: [dai@uri.edu](mailto:dai@uri.edu).

### **Anti-Discrimination Resources** 

Several offices provide support to help faculty comply with the University’s commitment to maintain an educational and working environment free from discrimination, and to uphold our collective obligation as a community to foster an inclusive, people-centered culture. 

### **Bias, Discrimination, Harassment, and Retaliation Reporting and Resources** 

Several teams and offices provide support to help faculty comply with the University’s commitment to maintain an educational and working environment free from bias, discrimination, harassment, and retaliation, with the ultimate goal of upholding our collective obligation as a community to foster an inclusive, people-centered culture. Those include (1) the [Bias Resource Team](https://web.uri.edu/brt/), which accepts and reviews bias reports for support and referral purposes; it does not function as an investigatory body; (2) the [Office of Equal Opportunity](https://web.uri.edu/equal-opportunity/) accepts complaints of discrimination, harassment, and retaliation, which are investigated in accordance with the Policy on Nondiscrimination and (3) the [Title IX Coordinator](https://web.uri.edu/titleix/know-your-title-ix/) accepts complaints of sex-based discrimination and harassment, which are reviewed for triaging or investigation in accordance with the Policy on Sexual Misconduct. University community members may use the University’s [Rhody Report It](https://web.uri.edu/enterprise-compliance/rhody-report-it/) tool to identify reporting options available to those raising allegations of bias, discrimination, harassment, and retaliation.

#### **Office of Equal Opportunity (OEO)**

[The Office of Equal Opportunity](https://web.uri.edu/equal-opportunity/) (OEO) leads institutional civil rights compliance efforts and supports the belief that all individuals have a right to enjoy equal opportunity in employment and equal access to all university programs, services, and activities, without regard to their protected status. OEO’s primary focus areas include: anti-discrimination, affirmative action, equal opportunity, Americans with Disabilities Act (ADA) and Rehabilitation Act Compliance, education & training, and language access. OEO is available to address inquiries from faculty, staff, students, and service recipients and to work with departments to promote compliance with the university’s Policy on Nondiscrimination, Policy on Language Access, the University’s Language Access Plan, and applicable civil rights laws and regulations.

#### **Title IX.**  

Any student, faculty, or staff member with questions or concerns about the Policy on Sexual Misconduct or who believes that they have been the victim of sex discrimination, sexual harassment, or sexual violence, as defined under Title IX, is encouraged to contact the University’s Title IX Coordinator. Matters involving employees that do not meet the burden of proof under Title IX are forwarded to the Office of Equal Opportunity and the Office of Human Resources. The Title IX Office, in collaboration with the Dean of Students, provides support for and ensures enforcement of the University’s Policy on Sexual Misconduct. The Title IX Coordinator also provides support to pregnant and parenting students, in collaboration with the Dean of Students, and to pregnant and parenting employees, in collaboration with the Office of Human Resources. Faculty with questions or concerns about potential sex-based discrimination or sex-based harassment violations, or departments seeking training, should contact the Title IX Coordinator at tixc@etal.uri.edu. More information is available at: [Know Your Title IX – Sexual Violence Prevention and Response](https://web.uri.edu/titleix/know-your-title-ix/).

#### **Providing equal access for students with disabilities** 

Every qualified student with a disability has the right to equal access to educational programs, services, activities, and facilities.  Documentation-supported accommodations are communicated to faculty through a letter from Disability, Access and Inclusion (DAI), delivered by the student.  Faculty are required by law to provide these accommodations and are encouraged to review the information on the [DAI website](https://web.uri.edu/disability/for-faculty-and-staff/). The [Academic Testing Center](https://web.uri.edu/atc/) is available to support testing accommodation needs. Students seeking accommodations in their roles as internal payroll employees should contact the Office of Human Resources. This includes Graduate Assistants and Graduate Research Assistants. Testing accommodations are administered by the Academic Testing Center and must be coordinated by the faculty. Visit [ADA Compliance – Office of Equal Opportunity](https://web.uri.edu/equal-opportunity/ada-compliance/) for a list of ADA Liaisons at the University of Rhode Island.

#### **Disability, Access, and Inclusion Drop-In Hours** 

Questions about student DAI accommodations? DAI staff are available each weekday from 2-4PM in their [webex room](https://urldefense.com/v3/__https://rhody.webex.com/meet/DAI__;!!Jh1S!hXAtz-ad8Hfj5n_0J1irHh2nY3L6EuhzNtbS2kd025XKxxqjW-WNP_3-of7wOYMNFIc7YIiceZbdiWbH-gyHUA$), or call 874-2098. DAI leadership also provides special Faculty WebEx Drop-in Hours, for the first month of the Fall and Spring semesters on Mondays from 11AM-1PM and Wednesdays from 8-10AM. Please also reach out to us at dai@uri.edu if you would like to discuss a Workshop for your department or colleagues, we can work with you to tailor this to your individual needs and interests.


### **Land Acknowledgement** {#land-acknowledgement}

The University of Rhode Island land acknowledgment is a statement written by members of the University community in close partnership with members of the Narragansett Tribe. The statement recognizes and pays tribute to the people who lived on and stewarded the land on which the University now resides. The statement seeks to show gratitude and respect to Indigenous people and cultures and build community with the Narragansett Nation and other Native American tribes.

**University of Rhode Island Land Acknowledgment**

*The University of Rhode Island occupies the traditional stomping ground of the Narragansett Nation and the Niantic People. We honor and respect the enduring and continuing relationship between the Indigenous people and this land by teaching and learning more about their history and present-day communities, and by becoming stewards of the land we, too, inhabit.*

### **Resources for Mental Health and Well-being** {#resources-for-mental-health-and-well-being}

Your mental health and well-being is very important to us. We all experience emotional distress and personal difficulties as a normal part of life. Sometimes, these struggles can interfere with our day-to-day functioning. As your instructor, I want to support your well-being and success and encourage you to reach out if you are having difficulty with this course. However, as I am not qualified to serve as your counselor, I want to share resources available should you be experiencing mental health distress and/or personal difficulties. URI Counseling Center offers free and confidential mental health services that are not connected to your academic record in any way. For more information, please visit the Counseling Center website at [https://web.uri.edu/counseling/](https://web.uri.edu/counseling/). Counseling Services, located in Roosevelt Hall, is open Monday-Friday 8:30 am-4:30 pm. To schedule an appointment, visit us at Roosevelt Hall, Room 217, or call us at 401-874-2288.

Additional resources for you or one of your peers:

●      In the event of an emergency, call 911 or Campus Police at 401-874-4910

●      For non-emergency mental health appointments with the URI Counseling Center, call 401-874-2288

●      Health Services, 6 Butterfield Rd, 401-874-2246

●      Psychological Consultation Center, located in Chafee, 401-874-4263

●      Couple and Family Therapy Clinic, 2 Lower College Road, 401-874-5956

●      24/7 Support Line: TELUS 1-844-584-1027

●      Call or text 988, National Suicide and Crisis Hotline

●      URI Report It Page for concerns with friends or yourself: [https://web.uri.edu/deanofstudents/report-it/](https://web.uri.edu/deanofstudents/report-it/)  

●      Student Bereavement Guidelines: [https://web.uri.edu/student-support/students/support/bereavement/bereavement-policy/](https://web.uri.edu/student-support/students/support/bereavement/bereavement-policy/)