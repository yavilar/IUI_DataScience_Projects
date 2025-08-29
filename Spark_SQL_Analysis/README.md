# Spark SQL Analysis

This project demonstrates how I used **Spark SQL** to query and analyze a dataset of wildlife trade records.  

## What I Did
- Set up a Spark SQL session in Google Colab.  
- Loaded a dataset of trade records with fields like Year, Taxon, Class, and Term.  
- Wrote SQL queries to answer key questions, such as:  
  - Which animal classes are most frequently traded?  
  - What items are associated with Mammalia?  
  - Which species fall under CITES Appendix II?  
  - What is the most common taxon traded in 2017?  
  - Which classes are involved in the trade of teeth, live specimens, and carvings?  

## What I Found
- **Reptilia** was the most frequently traded class.  
- Mammals were traded for a wide variety of items, including carvings, garments, and skins.  
- CITES Appendix II contained many of the most traded species.  
- In 2017, **Alligator mississippiensis** appeared as a top traded taxon.  
- Several classes (Mammalia, Reptilia, Aves, etc.) appeared in the trade of live specimens and carvings.  

## Skills Shown
- Spark SQL queries (GROUP BY, DISTINCT, ORDER BY, filtering).  
- Data exploration in a distributed environment.  
- Turning data into clear insights.  
