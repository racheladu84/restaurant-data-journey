# Module 1 Day 2: Dataset Exploration

## Dataset

**Dataset name:** pizzaplace  
**Source:** Rdatasets / gt  
**Source page:** https://vincentarelbundock.github.io/Rdatasets/doc/gt/pizzaplace.html

## What one row represents

One row represents one pizza sold. One order can contain more than one pizza, so the same order ID can appear on more than one row.

## Fields I can see
- `rownames`: A row number included in this CSV export. I will preserve it in the original file.
- `id`: The order ID. Several pizzas can share the same order ID.
- `date`: The date the order was placed.
- `time`: The time the order was placed.
- `name`: The short name of the pizza sold.
- `size`: The pizza size, such as S, M or L.
- `type`: The pizza category, such as classic, chicken, supreme or veggie.
- `price`: The amount that pizza sold for, in US dollars.

## Three questions this dataset can help answer

1.  Which pizza names were sold most frequently? I can count rows for each `name`.
2.  Which pizza categories generated the highest sales value? I can add up `price` for each `type`.
3. Which hours of the day had the most orders? I can group `time` by hour and count distinct `id` values.

## One question this dataset cannot answer well
The dataset has an order ID but no customer ID. I cannot tell whether two different orders were placed by the same customer.

## Why it cannot answer it
The dataset has an order ID but no customer ID. I cannot tell whether two different orders were placed by the same customer.

## Notes about provenance or limitations
Record anything important about where the data came from, what is synthetic or public, or any limitations you should remember.

