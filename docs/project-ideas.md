---
layout: default
---

<div class="message">
I prefer to supervise application development projects. I would welcome any suggestions you have for projects as I do not have any research projects to offer.
</div>

I have one idea which is outlined below. If you are interested in this, you will need to be prepared to think about how to solve the problem yourself.

### PGTA modelling and dashboard

PGTA = Post Graduate Teaching Assistant. PGTAs are typically, but not always, PhD students at UCL or other London universities. They may also be Research Fellows or Research Associates.

#### Problem statement

Each year the module leaders who teach the computer science modules individually make requests for a number of hours to be budgeted for PhD support for their teaching. These requests are centrally collated, reviewed and approved and then the roles on each module are advertised. Potential PGTAs then apply for the roles.

There are many challenges with the approach, however this project is specifically related to the following:

1. It is difficult to forecast the demand for PGTAs over a period of time. Some historical data exists but is not compiled in a way that makes past trend analysis visible to many.
2. There is no model to guide a new module as to what is a reasonable level of PGTA support for that module
3. Demand for PGTAs typically exceeds supply. It may be helpful to identify modules that have a lower or higher than expected PGTA demand given various factors about the module (e.g. number of students, number of contact hours, type of assessment etc.)

#### What the solution is likely to involve

1. **Demand modelling**. Consider the profile for CS modules such as number of students enrolled, assessment type (coursework/exam), class types (lecture, lab, tutorial), programming language or other skills needed, number of lecturers etc. Some of this data exists, other data you would need to find out yourself or determine how to deal with the NaNs. Given this data, is it possible to develop a model that allows us to predict the PGTA hours for a given module (or module type) in a year, based on the predicted number of students taking the module? Can such a model be used to provide a baseline to model the impact of introducing new modules on the PGTA supply? Can the model be used to predict future demand based on varying students numbers?

For this part there is no guidance about how to approach the problem. If you have some data analysis; statistics or machine learning background then you would ideally propose ideas for how to develop the model.
2. **Data dashboard**. Develop a PGTA data dashboard that will provide staff with information such as: PGTA demand versus supply; display over time the demand and supply of PGTA. This should give insight into current and histric data. It may also be useful as an interface to the model to predict demand.

For this part; I would prefer the dashboard to be developed using Python Plotly dash or streamlit as I would need to maintain it myself longer term.
