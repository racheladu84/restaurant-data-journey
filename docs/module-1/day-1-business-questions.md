# Module 1 Day 1: Business Question to Data Question

## Exercise purpose

This exercise helped me turn a broad business question into a question that can be answered with data.

## My questions

### Question 1

**Business question:** Which menu items generate the highest sales value?

**Data question:** What is the total sales value for each item in this extract?

**Fields or data needed:** Item, quantity and price.

**Can the current dataset answer it?** Partly. It has the fields needed to calculate sales value, but one record has no price,
so its sales value cannot be calculated without addressing that missing value.

### Question 2

**Business question:** Which times of day have the most order activity?

**Data question:** How many distinct order IDs appear in each hour of the day in this extract?

**Fields or data needed:** Order ID and time.

**Can the current dataset answer it?** Yes, for the dates covered by this extract. It contains both fields. I would count each order ID once so an order with more than one item is not counted twice.
## What I learned

Write 2 - 4 sentences about the difference between a business question and a data question.
I learned that a business question is a broad question about what the restaurant wants to understand.
A data question makes it more specific by looking at the available fields and deciding what can be measured or compared to help answer the business question.
