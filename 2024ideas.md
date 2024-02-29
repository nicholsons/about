# Ideas for 2024

Initial thoughts, not yet researched.

## 1. AI in teaching SQLite database design to beginner students

Learning objectives for the students:

- Know the normal forms to at least 3NF 
- Apply normalisation for a database based on a given data set to at least 3NF
- Understand there may be trade-off between a more normalised database design and query complexity
- Give opportunities for students to practice both database design and writing queries
- Be aware of how AI can be used (and/or its limitations) in database design

Format: A GitHub repo that students access, or a web app?

Rough outline:

- Take 10 data sets (with possibility to add more in the future).
- Create a tutorial that helps students to create a database normalised to 3NF Boyce-Codd (or possibly further?)
- It should work through each level showing the design at each stage and the differences
- Define a set of CRUD queries for the records in the database - show where these differ for the different levels
- Should work for a random choice of the 10 sample data sets.
- Incorporate the use of AI as far as possible e.g. can it help to generate the database design in ERD or other format at each level of normalisation?
  Can it write SQL queries based on a database design? If so, what format do you need to provide the design in?

To what extent can chat-GPT help?

- Can it create the designs at the different levels?
- Can it be used to test their solutions?
- Can it generate the queries?
- Can it assess what the benefits are of 3rd normal versus Boyce-Codd or higher?


## 2. Using AI diagram generators

To what extent is AI useful in designing a software application?

May be hard to automate this.

Research and find free tools that students could use to generate UML diagrams.
https://theresanaiforthat.com/s/class+diagram/

Write tutorial on how to create say a class diagram.

Give requirements for a REST API

Ask students to draw a class diagram.

Create 2-3 auto generated versions. Compare them to the students work. Critically review against design principles?

## 3. AI to generate infographics/charts
To what extent can AI tools be used to create infographics and charts for a Dash or Streamlit app?