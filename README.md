
# Job Dashboard for 2024 Job Posts

An interactive Power BI dashboard exploring data and IT-related job postings from 2024. The report brings together job demand, salary comparisons, hiring locations, and employment conditions to help users explore the job market and investigate roles that interest them.

## Project Reference

This project was developed with reference to **Power BI for Data Analytics - Full Course for Beginners**, a YouTube video by **Luke Barousse**.

## Dashboard Overview

The report contains two interactive pages: an overview for comparing jobs and a drill-through page for exploring a selected job title.

### Page 1 — Job Market Overview

The first page summarises the dataset and helps users compare roles and identify trends throughout 2024. It includes:

- **Total number of jobs:** the number of job postings in the current selection.
- **Average job rating:** a summary displayed using a star rating.
- **Yearly and hourly salaries:** median salary values in US dollars.
- **Jobs over time:** a line chart showing how posting volumes change during the year.
- **Yearly versus hourly pay:** a scatter plot comparing median annual and hourly salaries across job titles.
- **Salary rankings:** a bar chart comparing job titles by yearly pay.
- **Detailed job comparison:** a matrix combining posting counts, salary values, and trend sparklines.

The **Job Selection** dropdown allows users to select one or multiple roles to filter and compare on the overview page. Drill-through works with **one job title at a time**: click a single job in one of the visuals to activate the **Drill Through to Job Title** button.

![Page 1: Job market overview with job counts, salary comparisons, posting trends, and a job comparison matrix](images/page_1.png)

### Page 2 — Job Title Details

The second page provides a closer look at a selected job title. The screenshot below shows **Senior Data Scientist** as an example. This page includes:

- **Yearly and hourly salaries:** salary gauges summarising pay for the selected role in US dollars.
- **Work-from-home availability:** the proportion of postings marked as allowing remote work.
- **No degree mentioned:** the proportion of postings flagged as not mentioning a degree requirement.
- **Health insurance:** the proportion of postings marked as offering health insurance.
- **Global job distribution:** a map showing where postings for the selected role are located, with bubble sizes representing posting counts.
- **Job platforms:** a bar chart comparing the number of postings across recruitment platforms.
- **Employment types:** a treemap showing the proportions of full-time, contractor, part-time, temporary, and internship postings.

These details help users compare the opportunities, benefits, and employment arrangements associated with a role. A posting that does not mention a degree should not automatically be interpreted as confirming that no degree is required.

![Page 2: Senior Data Scientist drill-through with salaries, benefits, global locations, recruitment platforms, and employment types](images/page_2.png)

## Visualisations and Interactive Features

| Visual | Purpose |
| --- | --- |
| Cards and star rating | Summarise job counts, salaries, and job ratings |
| Line chart | Show changes in job-posting volume over time |
| Scatter plot | Compare yearly and hourly salaries across roles |
| Bar charts | Compare salary rankings and recruitment platforms |
| Matrix with sparklines | Present detailed job metrics alongside trends |
| Salary gauges | Display pay information for the selected role |
| Doughnut charts | Show the proportions of postings with selected benefits or requirements |
| Map | Show the geographic distribution of job postings |
| Treemap | Compare employment types by their share of postings |

The dashboard supports job-title filtering, interactive visual selections, and drill-through navigation. Users can move from the overview to a selected role's details using the drill-through button, then return using the back button.

## Video Demonstration

The recording demonstrates the dashboard and its interactive features. **The demonstration video contains no audio.**

[Watch or download the silent dashboard demonstration](images/Project_1_recording.mp4)

## Explore the Project

1. Download [Project_1.pbix](Project_1.pbix) and open it in Power BI Desktop.
2. Explore the overview page and use **Job Selection** to filter for one or multiple roles. Multiple selections apply to the overview page, but drill-through works with **one job title at a time**. Click a single job in one of the visuals, such as its bar in the salary chart or its row in the matrix, to activate the **Drill Through to Job Title** button.
3. Use **Drill Through to Job Title** to open the detailed page for the selected role.
4. Explore the salary, benefits, location, platform, and employment-type visuals, then use the back button to return to the overview.

The screenshots and recording provide a preview; open the Power BI file to interact with the report. All figures describe the postings represented in this project's dataset and the active filter selection.
