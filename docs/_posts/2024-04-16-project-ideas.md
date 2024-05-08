---
title: "Project ideas for 2024-25"
last_modified_at: 2024-08-05T00:00:00-00:00
---

# Ideas for 2024/25

These are very early stage thoughts and have not been investigated so these may not be suitable!

## 1. AI in teaching SQLite database design to beginner students

### The learners

This relates to COMP0035 Applied Software Engineering Learning which is a 3rd year IEP module for undergraduate
engineering students. It is part of the IEP minor in Application Programming for Data Science.

As part of the module, students will spend 2 weeks learning SQL database design. 2 weeks of the module learning would be
roughly 2 hours of lectures, 4 hours of tutorials and 12 hours of independent learning.

At the end of this the students should:

- Know the normal forms to at least 3NF
- Be able to apply normalisation for a database based on a given data set to at least 3NF
- Understand there may be trade-off between a more normalised database design and query complexity
- Write queries to retrieve data from a database with more than 1 table
- Be aware of how AI can be used (and/or its limitations) in database design

### Undergraduate dissertation suggestion

2 weeks is not much time to learn the material and then apply it to their coursework project. Students have to learn
several other topics as well during the term and apply them to their coursework.

The aim of this undergraduate dissertation project is to investigate the extent to which chat-GPT could be used to help
students learn more
quickly/effectively; and also to what extent it could help them with their coursework. You should then use the results
of the investigation to propose/design activities that would help students to make effective use of chat-GPT to learn
the topic.

### Possible approach and solution

- A GitHub repo that students access?
- Guidance on using chat-GPT specifically to learn the database concepts
- Create activities; and possibly provide unit tests that will allow students to test their solutions
- The activities should be able to be used with different datasets

Rough outline:

- Research how database design is taught, including if there are any recent papers on learning using chat-GPT
- Consider the implications of the research for the teaching in COMP0035
- Take 10 data sets (with possibility to add more in the future).
- Create a tutorial that helps students to create a database normalised to 3NF Boyce-Codd (or possibly further?)
- It should work through each level showing the design at each stage and the differences
- Define a set of CRUD queries for the records in the database - show where these differ for the different levels
- Should work for a random choice of the 10 sample data sets.

The activities must incorporate the use of AI as far as possible e.g.

- can it help to generate the database design in ERD or other format at each level of normalisation?
- Can it write SQL queries based on a database design? If so, what format do you need to provide the design in?
- Can it create a database design for a specified level of normalisation?
- Can it be used to test their solutions?
- Can it generate the queries?
- Can it assess what the benefits are of 3rd normal versus Boyce-Codd or higher?

## 2. Using AI to generate software design diagrams

Project concept: Investigate the extent to which AI is useful in designing a software application?

Research and find free tools that students could use to generate UML diagrams.
https://theresanaiforthat.com/s/class+diagram/

Write tutorial on how to create diagram, e.g. UML class diagram, database design ERD, etc

Give requirements for a Python web app, e.g. a simple REST API

Ask students to draw the relative diagram themselves (ie not using AI).

Create 2-3 auto generated versions. Compare them to the students work. Critically review against design principles?

## 3. Redesigning a Google apps solution (Google sheets, forms. apps script (JavaScript) and Microsoft PowerApps)

### The problem

The CS department recruits 200 PGTAs and around 30 Undergraduate interns to support its teaching each year. Last year
there were over 500 applications that had to be handled and over 300 contract requests and changes. The budget and
recruitment process is managed by me, and I also teach two large modules. The volume of changes and the number of emails
involved in the process is overwhelming for one person (i.e. for me!). If the amount of admin time can be reduced, I
could use the time gained on more value-add activities such as providing training for departmental PGTAs and
undergraduate teaching interns.

I inherited a solution based on Google sheets and forms. This works well as the Google
ecosystem is free to use and there is lots of documentation. Over the last two years I've extended the original
sheets / forms solution using Google apps script and a simple Google apps script web front end. The solution has grown
organically though and there is a lot of repetition and inefficiency. There is also one area that is significantly
limiting. To automate email notifications uses Google gmail and is limited to 100 per day, this is not sufficient for
the needs of the recruitment and is also not integtated with UCL mail so cannot be used. If a free solution can be found
to automate email notifications from UCL email when changes are made in the Google based system this would save
significant effort and improve the experience for applicants, module leaders, HR and me. I would also like to be able to
auto push data from Sheets to Excel (in Teams/Sharepoint) for HR to access. It may be possible to then use
Teams/Sharepoint as the basis to push out email notifications using Power Apps.

### Project idea

Look at how good software design practices can be applied to refactor and improve the solution e.g.

- Measure the current performance: response times; assess the efficiency (or otherwise) of the algorithms. Use software
  tools to do this.
- Diagram the current 'spaghetti' design; draw diagrams that reflect its current structure/architecture. You should be
  able to find tools that will automat this.
- Having identified the weaknesses, consider how the design can be improved while keeping the solution within the
  current platform (Google apps script, Google sheets, Google forms).
- Design and implement the changes, and then measure the revised solution again and compare the differences with the
  original solution to assess the improvement.
- Ideally, you should also find and implement a solution to the email notifications issue and sharing of data between
  Google and Microsoft platforms. There is no funding so any solution must use free features in Google/Microsoft Power
  Apps.