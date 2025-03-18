# nosql-challenge

This project is a comprehensive analysis of food hygiene ratings provided by the UK Food Standards Agency. It uses a MongoDB database to store data imported from a JSON file, and leverages PyMongo and Python’s Pandas library for data manipulation and exploratory analysis. The repository includes a Jupyter Notebook that sets up the database, performs necessary data transformations, and executes various queries to extract actionable insights—ranging from filtering establishments based on hygiene scores to aggregating local authority data. The project adheres to specific instructions provided by the editors of Eat Safe, Love, ensuring that the analysis meets both functional and performance requirements.

In this assignment, the project not only demonstrates database setup and update operations using MongoDB but also provides a detailed exploratory analysis to help food critics and journalists target their future articles effectively. The notebook walks through essential steps including data import, insertion of a new restaurant record, cleanup of unwanted data, and conversion of string number fields to numeric types. Finally, it uses aggregation pipelines and advanced querying techniques to answer key questions, such as identifying establishments with specific hygiene scores and highlighting the top-rated venues near a new restaurant. This repository is structured for clarity and reproducibility, making it easy for other developers or stakeholders to review and extend the analysis as needed.