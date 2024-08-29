# nosql-challenge
- Module 12 Challenge
- Steph Abegg

## Task
For this module’s Challenge, we were tasked with importing a JSON file of food establishment ratings data to a MongoDB database and conducting analysis to help a food magazine make decisions about their future articles. 

## Deliverables 

This Challenge had two Deliverables:

1. Deliverable 1: A Jupyter notebook ([NoSQL_setup.ipynb](NoSQL_setup.ipynb)) containing code that imports the data and sets up and updates the uk_food database.

2. Deliverable 2: A Jupyter notebook ([NoSQL_analysis.ipynb](NoSQL_analysis.ipynb)) containing code that performs the exploratory analysis queries in the database.

## Analysis Summary

There are 41 establishments with a hygiene score of 20.

There are 33 establishments in London with a RatingValue greater than or equal to 4.

The Business names of the top 5 establishments with a Rating Value of 5, sorted by lowest hygiene score, within 0.01 degree of the 'Penang Flavours' restaurant: "Howe and Co Fish and Chips - Van 17", "Lumbini Grocery Ltd T/A Al-Iman", "Plumstead Manor Nursery", "Iceland", "Volunteer"

There are 55 Local Authority areas that have at least one establishment with hygiene score of 0. The first 10 Local Authority areas, sorted by number of establisments with a hygiene score of 0, are:
<img src="hygiene_agg_df_first10.png" width=300>

