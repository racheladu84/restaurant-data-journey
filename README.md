# Restaurant Data Journey: From Transactions to Business Insights

## About This Portfolio

This portfolio documents my learning journey through the Coding Black Females Introduction to Data Science short course.

Across six modules, I will build evidence of my work in data quality, SQL, data warehousing, BigQuery, and data visualisation.

## Tools

- Google Sheets
- GitHub
- Visual Studio Code
- SQL
- BigQuery

## Module 1: Introduction to Data
### Day 1 Evidence

- [Data Detective exercise](docs/module-1/day-1-data-detective.md)
- [Business Question to Data Question exercise](docs/module-1/day-1-business-questions.md)

### Day 1 Reflection

One thing I understand more clearly about data now is:  
I can recognise different classifications of data and identify whether an example is quantitative or qualitative.

One example of quantitative data and one example of qualitative data is: 
A menu price is quantitative and a customer review is qualitative 

One question I would like to answer using restaurant data is:
What type of food sells the most during busy and slow days

One concept I want to practise further is: 
Turning a broad business question into a specific data question and checking which fields are needed to answer it.

### Dataset and Provenance

**Dataset:** pizzaplace  
**Description:** A year of pizza sales from a pizza place  
**Source:** Rdatasets / gt  
**Source link:** https://vincentarelbundock.github.io/Rdatasets/doc/gt/pizzaplace.html  
**Raw file location in this repository:** `data/raw/pizzaplace_original.csv`

**What one row represents:** One pizza sold. An order may contain more than one pizza, so the same order ID can appear on multiple rows.

### Initial Business Questions

1. Which pizzas sell most frequently?
2. Which pizza categories generate the greatest sales value?
3. How does sales activity change over time?

### Current Dataset Limitations

The dataset does not include fields such as customer ID, ingredient cost, employee ID or branch. This means some business questions cannot be answered from this dataset alone.

### Day 2 Evidence

- [Dataset exploration](docs/module-1/day-2-dataset-exploration.md)
- Raw dataset: `data/raw/pizzaplace.csv`

### Day 2 Reflection

**One thing I learned about using public datasets responsibly is:**  
Record where a dataset comes from and check for potential limitation before drawing a concrete conclusion from it.

**One thing I documented clearly in my portfolio workspace is:**  
documentation of each field name, what each row represents 

**One limitation of the dataset that I need to remember is:**  
It has an order IDs but no customer id, so its difficult to tell which customers placed repeat orders

**One question I want to carry into Module 2 is:**  
checking the quality of data before using it for any analysis


