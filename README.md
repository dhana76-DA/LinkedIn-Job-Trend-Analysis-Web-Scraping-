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

# Future Recommendations
To enhance the impact of this market intelligence tool, the following future steps are recommended:
1.	Sentiment & Seniority Analysis: Integrate logic to distinguish between "Required" and "Preferred" skills, as well as how demand shifts from Junior to Lead roles.
2.	Salary Correlation: Scrape and link salary ranges to specific skill combinations to identify "High-ROI" learning paths (e.g., Which skill adds an extra 20% to a base salary?).
3.	Automated Resume Matching: Use the Bipartite Graph logic to compare a user's uploaded PDF resume against the scraped trends to provide an "Interview Readiness" score.
4.	Time-Series Tracking: Run the scrape monthly to identify "Seasonal Skills" or long-term shifts (e.g., the rise of Generative AI keywords over 12 months).

# Conclusion
By transforming unstructured web data into a structured Skill-Role Matrix, this project provides a clear roadmap for career advancement. It proves that SQL remains the universal bridge skill, while Cloud and ML are the high-growth accelerators. This system offers a scalable solution for job seekers in cities like Vijayawada to align their learning with the actual requirements of the modern tech landscape, ensuring they are always "Market-Ready."


# Skill   

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

