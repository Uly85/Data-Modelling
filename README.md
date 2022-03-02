# Data-Modelling

- Determine how and when to use each data modeling component 

- Apply techniques to elicit data requirements as a prerequisite to building a data model 

- Build relational and dimensional business terms, logical, and physical data models 

- Assess the quality of a data model 

- Incorporate supportability and extensibility features into the data model

**Data Model Assessment : Definitions, Consistency, and Data Profiling** 

A candy manufacturer is building a consumer feedback application, and they have hired you to review their data model. They have provided the following information to help you with this review.

There is a requirement to build a business application that reports trends on consumer interactions. An interaction is a contact between an employee and a consumer for a specific product. An interaction can take place through a variety of mediums such as through phone, email, and mail. Interactions fit into one of three categories: complaints, compliments, and questions. Here are examples of some of the interactions:

"I love your product." (compliment)

"I hate your product." (complaint)

"I found a strange object in your product." (complaint)

"Where can I buy your product?" (question)

"I found your product difficult to assemble." (complaint)

A consumer can have many interactions on many products. For example, Bob can call Monday because he did not like Product XYZ, he can call Tuesday and say that he now liked Product XYZ, and can call Wednesday and say that he loves Product ABC.

The requirement is to produce a report for each product that shows for the previous 12 months, the number of complaints, compliments, and questions. 
This report has to allow the users to "drill down" to get to the interaction level of detail and see the actual interaction such as “Loved product”.



