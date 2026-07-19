# Week 5 Assignment - Apache Spark DataFrames

# Objective

The objective of this assignment is to understand Apache Spark fundamentals and perform data cleaning, transformation, and aggregation using Spark DataFrames. The assignment demonstrates how Spark efficiently processes large datasets using in-memory computation.

---

# Technologies Used

- Python
- Apache Spark (PySpark)
- Google Colab
- Pandas

---

# Dataset

- Sample - Superstore Dataset

---

# Assignment Tasks

- Studied the limitations of Hadoop MapReduce.
- Understood the advantages of Apache Spark such as in-memory processing and faster execution.
- Learned Spark DataFrame concepts and immutability.
- Removed duplicate records.
- Handled missing and inconsistent values.
- Applied filtering on Region and Category.
- Performed aggregation using:
  - Count
  - Sum
  - Average
  - Minimum
  - Maximum
- Used `groupBy()` for grouped analysis.
- Renamed DataFrame columns.
- Understood Wide Transformations and Shuffle operations.
- Built a complete data processing pipeline combining cleaning and aggregation.

---

# Results

The assignment successfully demonstrated:

- Data cleaning using Spark DataFrames
- Filtering and transformation of records
- Aggregation and grouped analysis
- Schema modification
- End-to-end Spark data processing pipeline

#Sample Outputs

- Total Sales: **2,297,200.86**
- Average Sales: **229.86**
- Technology category generated the highest sales.
- West region had the highest number of orders.

---

# Key Learnings

- Spark is significantly faster than MapReduce because of in-memory processing.
- Spark DataFrames provide optimized distributed data processing.
- Transformations are immutable and create new DataFrames.
- GroupBy operations perform efficient large-scale aggregation.
- Wide transformations involve shuffle operations between partitions.

---

# Repository Contents

```
├── README.md
├── Week5_Assignment.ipynb
├── celebal_assignment_week5.pdf
└── Sample - Superstore.csv
```

---

## Conclusion

This assignment provided practical experience with Apache Spark DataFrames, including data cleaning, filtering, aggregation, schema modification, and pipeline creation. Spark's distributed in-memory architecture makes it a powerful framework for large-scale data analytics.
