This is an analysis on e-commerce customers and their shopping behaviours.

We are giving 3 datasets. One containing customers, another containing products and one more containing a map for the product categories.

---

## Part 1. Dataset Cleaning
In part 1, we clean the datasets using `numpy` and `pandas`. For the products datasets, we clean it and combine it with the product categories dataset for easy access. We format the customers' dataset by editing and combining its columns. We then export the formatted datasets to the `datasets` folder to be used in part 2.

<br>

## Part 2. Customer Segmentation
In part 2, we use the formatted datasets to cluster the customers based on their shopping behaviours. We plot the clusters on a graph using `plotly`.

---

## Results
![customers' plot](https://github.com/user-attachments/assets/88e275fd-9f9e-4072-97cb-e0ba534ace20)

This is the plot we end up with. We can see that their are 2 types of customers:
- The first group are low-income customers who therefore do not purchase much
- The second group are higher-income custoemrs who can afford to purchase more products
