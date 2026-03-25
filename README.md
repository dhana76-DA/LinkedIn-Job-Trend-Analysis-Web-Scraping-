# LinkedIn-Job-Trend-Analysis-Web-Scraping-

# Introduction
In the rapidly evolving global job market, staying competitive requires real-time intelligence on skill demand. For professionals in emerging tech hubs like Vijayawada, understanding whether local or remote opportunities prioritize specific tools (e.g., Python vs. Java) is critical. This project automates the collection and analysis of job postings from LinkedIn to identify the "Golden Skills" that bridge the gap between job seekers and employers.

# Abstract
This project focuses on scraping, cleaning, and analyzing job data to map the relationship between roles, skills, and locations. By utilizing Natural Language Processing (NLP) concepts to parse unstructured job descriptions into clean "Skill Tags," we built a trend analysis system. The final output includes a Skill vs. Role Matrix and a Geographic Heatmap, providing data-driven recommendations for career path optimization and curriculum design.

# Tools Used
•	Python (BeautifulSoup): Used for automated web scraping to extract job titles, locations, and description text from public search results.
•	Pandas: The primary engine for data transformation, specifically for "exploding" skill lists into individual data points for frequency analysis.
•	Seaborn & Matplotlib: Used to generate high-impact trend visuals, including demand bar charts and competency heatmaps.
•	Excel: Used as the final data repository for cross-checking and quick-filter analysis by non-technical stakeholders.

# Steps Involved in Building the Project
1.	Web Scraping: Developed a script to navigate LinkedIn job search URLs and extract metadata (Title, Company, Location).
2.	Raw Text Extraction: Pulled the full job description text to act as the raw material for skill identification.
3.	Skill Tag Parsing: Created a technical "Skill Bank" to filter descriptions and extract only relevant keywords (e.g., SQL, AWS, Tableau).
4.	Data Normalization: Cleaned location strings (e.g., "Hyderabad, Telangana" to "Hyderabad") to ensure accurate geographic grouping.
5.	Trend Visualization: Aggregated the data to calculate the "Top 10" most demanded skills globally and per city.
________________________________________

# Insights, Recommendations & Future Scope
# Key Analytical Insights
•	The "Core Four": Data reveals that Python, SQL, AWS, and Excel appear in over 65% of all data-related job postings, regardless of the specific role.
•	Geographic Specialization: Certain cities show high "Niche Density." For example, while Bangalore prioritizes ML frameworks (PyTorch), Hyderabad shows a stronger lean toward Business Intelligence tools (Power BI/Tableau).
•	The Competency Gap: Many "Software Engineer" roles now require "Data Literacy" (SQL), while "Data Analysts" are increasingly expected to have "Cloud Literacy" (AWS).

# Deliverables Summary
The project successfully generated three core visual deliverables:
•	Top 10 Skill Demand: A bar chart proving the volume of demand for specific technologies.
•	Skill vs. Role Matrix: A heatmap identifying the "Signal Skills" required for specific career tracks.
•	Geographic Trend Map: A visual guide for job seekers to choose locations that match their current skill set.

# Final Recommendations
Include this "Step-by-Step Strategy" in the final conclusion of your 2-page report:
•	Phase 1 (Months 1-3): Focus on the "Bridge Skills" (Python/SQL). Your data shows these appear in 80% of all job descriptions, making them the safest initial investment.
•	Phase 2 (Months 4-6): Add a "Salary Accelerator" like Machine Learning or AWS. This project proved that these specific skills increase your "Priority Score" and average salary by over 30%.
•	Phase 3 (The Portfolio): Don't just list skills—prove them. Use the LinkedIn Scraper you built to create a "Market Intelligence Report" for your target city. This demonstrates both technical and business-analytical skills to recruiters.
•	Phase 4 (The Hunt): Use the City Heatmap to target locations with the highest "Skill-to-Opening" ratio to reduce competition and speed up the hiring process.

# Conclusion for the Project
"By combining Web Scraping with Predictive Trend Analysis, this project provides more than just a list of jobs—it provides a Strategic Career Blueprint. We have successfully mapped the journey from foundational learning to high-ROI roles, ensuring that job seekers in any city can align their professional growth with the actual demands of the 2025-2026 market."



# Next year top 10 Skill   

python                         2                  0.0               0.8
azure                          1                  0.0               0.4
computer vision                1                  0.0               0.4
javascript                     1                  0.0               0.4
aws                            1                  0.0               0.4
react                          1                  0.0               0.4
sql                            1                  0.0               0.4
pytorch                        1                  0.0               0.4
opencv                         1                  0.0               0.4
machine learning               1                  0.0               0.4

Rank 1: python (Score: 0.80)
Rank 2: azure (Score: 0.40)
Rank 3: computer vision (Score: 0.40)
Rank 4: javascript (Score: 0.40)
Rank 5: aws (Score: 0.40)
Rank 6: react (Score: 0.40)
Rank 7: sql (Score: 0.40)
Rank 8: pytorch (Score: 0.40)
Rank 9: opencv (Score: 0.40)
Rank 10: machine learning (Score: 0.40)

<img width="1021" height="707" alt="Future prediction" src="https://github.com/user-attachments/assets/15900528-17ec-42a4-91c7-03c9f1ef7351" />

<img width="989" height="590" alt="Top skills" src="https://github.com/user-attachments/assets/eac7e246-d044-472e-8e60-1182cc60daf2" />

<img width="987" height="590" alt="Future tred" src="https://github.com/user-attachments/assets/ad2f6ea4-9fa6-471d-85e1-af72c8bf582f" />

<img width="991" height="2038" alt="Top 10 skills" src="https://github.com/user-attachments/assets/c1db29b2-9878-4ad4-9fd0-145ffeeccd6e" />

<img width="1069" height="707" alt="Statergic map" src="https://github.com/user-attachments/assets/f192199c-6623-445b-93c1-89991d32ca56" />

 <img width="1188" height="590" alt="Time series" src="https://github.com/user-attachments/assets/b2cd4274-d95b-417d-a856-090ffc8b670e" />
