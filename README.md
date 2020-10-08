# SQL-Workshop-Self-Cross-JOINs

## Short Description

This repository is a follow up to questions asked during the UCSF Library DSI workshops on introductory SQL and Python. 

## Long Description 

During the most recent workshop, we covered core SQL, including SELECT, WHERE, JOIN, and GROUP BY. Several participants were interested in more information specifically about how JOINs work, including CROSS JOIN, and self JOIN. This repository contains workbooks that provide examples and illustrate these concepts.

The workbooks in this tutorial use Python and the PandaSQL module to run SQL statements on Pandas Dataframes. 

## Prerequisites

You'll need familiarity with core SQL to follow along with these examples. To run the notebooks, you'll need introductory level experience writing Python code in Jupyter notebook (though you could transfer the code samples to a different IDE). 

## Workbooks

This tutorial consists of a series of notebooks. Further explanatory text is available in the notebook for each section or the tutorial. 

### Cross-Join-Example.ipynb

This notebook contains code illustrating the difference between an INNER JOIN and a CROSS JOIN. 

### State-Cases.ipynb

This notebook uses SQL snd COVID-19 data from the CDC to analyze COVID cases at the statewide level. Self-JOINs and CROSS JOIN techniques are illustrated by finding states with similar COVID case counts. 

### Cumulative-ER-Arrivals.ipynb

This notebook provides an example of using a self-JOIN to calculate the cumulative sum of arrivals to an ER, as well as a python/pandas method to accomplish the same thing. This notebook also contains techniques to create sample databases through code. 

### Left-Outer-Self-Join

This notebook demonstrates the use of a left outer self join. Example query covers how to include columns in an aggregation query that are not part of a GROUP. The bare column problem and how implementation can differ between databases. 

### ER-Visits-Changes.ipynb

More advanced use of self-JOIN and aggregations to analyze data at a granular level, based on a log of the date of arrival of each patient to the ER. 

### Find-Duplicates.ipynb

Finding duplicate rows in a table

