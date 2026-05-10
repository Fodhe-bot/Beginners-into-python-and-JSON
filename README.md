# Json-beginners
Just for future data engineers looking for an answer on nested JSON
I also added some Python intro and how to clean data. 

#For data_cleaned_for ML, there are going to be two codes to see the differences 
I realized the initial cleaning was over-processing the data and losing the semantic meaning. I adjusted the pipeline to preserve structural boundaries (like newlines) and critical data patterns (like decimals and email symbols) to ensure the data remains useful for downstream analysis

Hit a lot of walls with this new code, so I refactored the spellcheck logic and optimized it via AI-assisted debugging to preserve technical terms.
The Data Cleaning Challenge

Task: Build a pipeline to standardize messy, unstructured text for machine learning.

Action: Used Python, Regex, and ftfy to fix encoding, expand contractions, and mask PII (Emails/Phones).   

Learning: Discovered that aggressive spell-checking corrupted technical terms like HTML. Solved this by implementing a Technical Whitelist.   


Result: Created a reusable ETL script that preserves data integrity while removing 100% of the noise.
