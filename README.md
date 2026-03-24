# Internship Learning Journal  
**Name:** Badarish Malagi 
**USN:** 2BL22CS039 
**GitHub Username:** badarishm
**Department:** CSE
**Internship Start Date:** 03-02-2026

---

## 📌 Objective
This repository documents my learning journey during the internship.  
All notes, assignments, and project learnings are organized module-wise and chapter-wise.

---

## 🗂 Course Reference
Course Link: https://tds.s-anand.net/#/

---

## 📚 Modules Covered

| Module | Topics | Status |
|--------|--------|--------|
| Module 01 | Foundations | Completed |
| Module 02 | Tools & Implementation | Completed |
| Module 03 | LLM Concepts, Embeddings, RAG, Multimodal & Deployment	 | Completed |
| Module 04 | Data Sourcing, API usage, Automation, AI-based scraping, Web scraping | Completed |
| Module 05 | Data Preparation, JSON & Media Data, Cleaning, DuckDB, Shell Processing, dbt, OpenRefine |	Completed |
| Module 06 | Data Analysis, Excel Analysis, Correlation, Regression, Forecasting, Outlier Detection, Python Analysis, SQL Analysis, Datasette, DuckDB, AI Analysis, Geospatial Analysis, Network Analysis | Completed |
| Module 07 | Data Visualization, Data Storytelling, Presentation Tools, Excel Visualization, Forecast Visualization, Static Visualization, Animated Visualization, Network Visualization, AI Visualization, LLM Storytelling | Completed |

---

## ✍️ How to Use This Repository
- Each **module** has its own folder  
- Each **chapter** has a separate markdown file  
- Record:
  - Key concepts  
  - Examples  
  - Commands / code snippets  
  - Doubts  
  - Learnings  

---

## 🚀 Key Learnings So Far
# Week 1 – Learnings

Week 1 focused on building the foundational setup and understanding the essential tools required for development in the TDS course.



1. Set up WSL (Windows Subsystem for Linux) and installed Ubuntu to create a Linux-based development environment on Windows.
2. Learned the importance of Linux in real-world development and why many tools work better in a Unix-like environment.
3. Understood how to use the terminal and execute basic Linux commands.
4. Navigated the Linux file system using commands like cd, ls, pwd, mkdir, etc.
5. Learned the difference between absolute paths and relative paths.
6. Understood key Linux directories and how files are structured.
7. Installed Git and understood its role in version control.
8. Created a GitHub account and linked it with the local system.
9. Generated SSH keys for secure authentication with GitHub.
10. Learned how SSH improves security compared to HTTPS.
11. Created repositories on GitHub.
12. Cloned repositories locally using SSH.
13. Made local changes and pushed them back to GitHub.
14. Learned commit workflow:
    - git add
    - git commit
    - git push
15. Understood the importance of version tracking and collaboration.
16. Integrated VS Code with WSL for seamless development.
17. Used the VS Code terminal to run Linux commands.
18. Learned the importance of APIs in modern applications.
19. Understood how tools and workflows are as important as coding.
20. Built a strong foundation for working in a collaborative development environment.



# Week 2 – Learnings

In Week 2, I moved from basic setup into hands-on development, deployment, and AI tool integration.



1. Learned how containerization works using Podman and understood how containers isolate applications along with their dependencies.

2. Deployed development tools like Jupyter Lab and local LLMs inside containers and learned how to manage container lifecycle.

3. Understood port binding and volume mounting to make container services accessible and persist data.

4. Explored container networking to allow communication between multiple services such as backend apps and AI models.

5. Built a FastAPI application and learned how APIs are structured using routes, requests, and responses.

6. Practiced handling GET and POST requests in FastAPI and understood how backend services interact with frontend or external tools.

7. Learned how to deploy applications using platforms like Hugging Face Spaces and GitHub Pages.

8. Understood real-world deployment challenges such as environment configuration and runtime limitations.

9. Used GitHub Codespaces for cloud-based development without relying on local machine setup.

10. Learned how GitHub Actions can automate workflows like testing and deployment.

11. Integrated LLM tools into development workflows and understood how APIs connect AI models to applications.

12. Practiced managing API keys securely using environment variables.

13. Understood how development workflows improve when tools like containers, APIs, and automation are combined.

14. Learned how real-world applications connect backend logic with AI capabilities.

15. Improved repository structure by organizing chapters, notes, and hands-on learnings for better documentation.


#  Week 3 – Learnings

In Week 3, I focused on understanding how modern AI systems work using embeddings, vector databases, RAG, APIs, and function calling, along with practical implementation.



1. Learned how Large Language Models (LLMs) work using tokens, transformers, and self-attention mechanisms.

2. Understood how APIs connect applications to AI models and practiced making API calls using httpx and curl.

3. Learned how to securely manage API keys using environment variables and `.bashrc`.

4. Built chatbot systems using structured conversation roles:
   - system
   - user
   - assistant

5. Learned how embeddings convert text and images into vectors for semantic understanding.

6. Used similarity techniques such as cosine similarity and vector distance to retrieve meaningful results.

7. Understood how vector databases store embeddings for fast similarity search.

8. Learned Retrieval Augmented Generation (RAG) to improve response accuracy by retrieving relevant data.

9. Implemented Hybrid RAG by combining similarity-based retrieval with structured search.

10. Practiced chunking large documents into smaller sections to stay within token limits.

11. Learned how multimodal models process both text and images using Base64 encoding.

12. Extracted structured data using function calling and defined schemas for automation.

13. Built similarity-based question answering systems using embeddings.

14. Used NumPy for vector operations and async API calls for better performance.

15. Understood the importance of prompt engineering for improving LLM responses.

16. Learned about evaluation techniques to ensure reliability and cost efficiency.

17. Debugged API issues and deployment problems related to FastAPI and environment configuration.

18. Understood how agents and tools help automate complex workflows.

19. Applied these concepts in Project 1 using embeddings and retrieval logic.

20. Learned how secure API handling and structured workflows are essential for real-world AI applications.


#  Week 4 – Learnings

In Week 4, I learned how to collect, extract, and automate data using spreadsheets, APIs, web scraping tools, and AI-based techniques.


1. Learned how to source data using spreadsheets like Excel and Google Sheets.

2. Practiced basic scraping using spreadsheet functions for simple data extraction.

3. Used command-line tools to crawl websites and collect structured information.

4. Retrieved data from APIs such as:
   - BBC Weather API
   - Nominatim API
   - Wikipedia API

5. Scraped web data using JavaScript from websites like IMDb.

6. Automated browser tasks using Playwright for dynamic content scraping.

7. Extracted structured data from PDF documents using Tabula.

8. Converted PDFs and HTML content into Markdown for easier processing.

9. Used AI-based tools to scrape and extract information from websites.

10. Applied AI techniques to extract insights from video content.

11. Learned how to schedule scraping tasks using GitHub Actions.

12. Worked with real-world data sources like emarketer.

13. Understood how automation improves scalability of data collection.

14. Learned how to transform raw scraped data into meaningful insights.

15. Explored how combining APIs, automation, and AI improves data sourcing workflows.

# Week 5 – Learnings

In Week 5, I learned how to clean, transform, and prepare raw data using spreadsheets, command-line tools, databases, and specialized data preparation tools.


1. Learned how to clean messy datasets in Excel by removing duplicates, correcting errors, and standardizing formats.

2. Practiced data transformation in Excel to restructure raw data into a more usable format.

3. Split combined text fields into multiple columns to improve data organization and analysis.

4. Performed data aggregation to summarize large datasets and extract useful insights.

5. Used command-line tools to clean and transform data efficiently.

6. Edited and processed datasets directly using terminal-based editors.

7. Learned how shell tools help automate repetitive data preparation tasks.

8. Used DuckDB to process and analyze large datasets efficiently using SQL queries.

9. Applied dbt to organize and manage structured data transformation workflows.

10. Used OpenRefine for advanced data cleaning tasks such as clustering and normalization.

11. Parsed JSON data into structured formats that can be easily analyzed.

12. Transformed and processed images for structured data use.

13. Extracted audio from media files and generated transcripts for further processing.

14. Learned how data preparation improves data quality and reliability for analysis.

15. Understood that proper data cleaning and transformation are essential before performing any analysis or building 


# Week 6 – Learnings 

This module focused on understanding different techniques and tools used to analyze datasets and extract meaningful insights.


1. Learned how to perform **data analysis using Excel**, including organizing datasets, filtering values, and calculating statistics.

2. Explored **correlation analysis in Excel** to understand relationships between variables and determine how strongly two variables are related.

3. Practiced **regression analysis in Excel** to model relationships between variables and predict future outcomes based on historical data.

4. Learned **forecasting techniques in Excel** to predict trends and future values using existing data patterns.

5. Studied **outlier detection in Excel**, identifying unusual or extreme values that can affect the accuracy of analysis.

6. Performed **data analysis using Python**, using libraries and scripts to process, analyze, and visualize datasets programmatically.

7. Learned how to analyze data using **SQL queries**, allowing efficient data exploration directly within databases.

8. Explored **database-based analysis tools** like Datasette and DuckDB to perform fast queries and analysis on structured datasets.

9. Understood how **AI-assisted analysis (Vibe Analysis)** can use LLMs to automate exploration, cleaning, modeling, and visualization of data. :contentReference[oaicite:0]{index=0}

10. Learned **geospatial data analysis**, working with location-based data using Excel, Python, and GIS tools like QGIS.

11. Studied **network analysis in Python** to analyze relationships and connections between entities in datasets.

12. Understood how combining different tools (Excel, Python, SQL, databases, and AI) can provide powerful insights from complex data.

#  Week 7 – Learnings

1. Learned the importance of data visualization in presenting complex data in a simple and understandable format.

2. Understood the concept of data storytelling and how visuals help communicate insights effectively.

3. Explored presentation tools like RevealJS and Marp for creating structured, code-based presentations.

4. Learned how interactive notebooks like Marimo combine code, visuals, and explanations in one place.

5. Practiced creating charts in Excel for quick and basic data visualization.

6. Learned how to visualize forecasts in Excel to predict future trends using historical data.

7. Explored static visualization tools like RAWGraphs for quick chart generation.

8. Used Python libraries like Seaborn to create advanced statistical visualizations.

9. Understood the difference between static and dynamic visualizations.

10. Learned how to create animated visualizations using tools like PowerPoint.

11. Explored platforms like Flourish to create interactive and animated data visualizations.

12. Studied network visualization using tools like Kumu to represent relationships between entities.

13. Learned about actor network visualization for understanding connections in systems.

14. Explored AI-based visualization using ChatGPT for generating insights and explaining data.

15. Understood how LLMs can be used for data storytelling and automated insight generation.



---

## ❓ Doubts / Topics to Revisit
- Topic 1  
- Topic 2  

---

## 🔄 Weekly Update Log
| Week | What I Learned |
|------|----------------|
| Week 1 | In Week 1, I set up a Linux-based development environment using WSL and learned essential terminal and file system navigation skills.I installed and configured Git and GitHub, including SSH authentication, to manage version control and collaboration.|
| Week 2 |In Week 2, I learned how to build and deploy applications using containers, FastAPI, and cloud platforms like GitHub Pages and Hugging Face.I gained hands-on experience with container networking, API integration, and managing secure environment configurations.|
| Week 3 | Learned how AI systems use embeddings, vector databases, and RAG to retrieve and generate meaningful responses.I practiced working with APIs, multimodal data, function calling, and similarity-based search techniques. |
| Week 4 | Learned how to collect and extract data using spreadsheets, APIs, and web scraping tools.And practiced automating data collection using Playwright, CLI tools, and GitHub Actions. |
| Week 5 | Learned how to clean, transform, and prepare raw data using tools like Excel, command-line utilities, DuckDB, and OpenRefine.Practiced working with structured and semi-structured data such as JSON, images, and audio transcripts. |
| Week 6 | Learned how to analyze datasets using different tools such as Excel, Python, SQL, and database systems. I explored techniques like correlation, regression, forecasting, and outlier detection to understand relationships and patterns in data. I also learned advanced topics such as AI-assisted analysis, geospatial analysis, and network analysis to extract deeper insights from complex datasets. | 
| Week 7 | Learned how to visualize data using tools like Excel, Python, and visualization platforms. I explored different types of charts, dashboards, and animated visualizations to present data effectively. I also learned how AI and LLMs can enhance data storytelling and generate insights. |

---




