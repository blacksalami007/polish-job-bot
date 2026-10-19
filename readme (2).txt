Polish Job Match Bot
Project Overview

Polish Job Match Bot is a personal Python project designed to help job seekers discover relevant employment opportunities in Poland. It uses the Jooble REST API to retrieve job listings and filter them according to language skills, technical knowledge, job preferences, and Polish-language requirements.

The goal is to make job searching more efficient by identifying relevant opportunities and organizing their links in an easy-to-review CSV file.

Main Features
Automated job searches: Searches for relevant vacancies using keywords related to customer service, IT support, helpdesk, technical support, back-office operations, and other entry-level positions.
Multilingual job matching: Prioritizes opportunities involving English, French, and Arabic.
Polish-language filtering: Excludes listings that explicitly require native or fluent Polish or C1/C2 proficiency, while flagging ambiguous language requirements for manual review.
Entry-level opportunities: Identifies suitable junior positions and roles that may accept candidates without extensive professional experience.
Relevance scoring: Assigns scores to job listings based on matching skills and keywords.
CSV export: Saves matching vacancies with job titles, company names, locations, available salary information, relevance scores, and direct links.
Duplicate handling: Organizes search results by listing URL to reduce duplicate entries.
Technology Stack
Python
Jooble REST API
JSON and HTTP requests
CSV for exporting results
SQLite for optional persistent storage
Intended Use

This project is intended for personal job-search assistance. It helps organize publicly available job listings and identify potential opportunities based on an individual's language skills and technical knowledge.

All job listings should be reviewed on their original websites before applying. Matching scores are estimates and do not guarantee eligibility or employment.

Privacy and Responsible Use

API credentials should be stored securely and should not be committed to public repositories. Job data is used to support personal research and application preparation.

The project accesses listings through an authorized job-search API rather than attempting to bypass website access restrictions.

Project Status

Personal project under development. Search coverage and matching accuracy depend on the availability and quality of data returned by the job-search API.

Future Improvements
More precise CV-based matching.
Improved language-requirement detection.
Additional permitted job-search data sources.
Notifications when new matching opportunities are found.
Filters for salary, location, remote work, and experience requirements.