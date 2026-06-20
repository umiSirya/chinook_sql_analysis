# Chinook Database SQL Analysis
**AnalystLab Africa Data Analytics Internship — Week 3**

## Overview
This project contains SQL queries written to analyse the Chinook music store database using MySQL Workbench. The Chinook database simulates a digital music store and includes data on artists, albums, tracks, customers, invoices, and employees.

## Dataset
- **Source:** https://github.com/lerocha/chinook-database
- **Tool:** MySQL Workbench
- **Database:** MySQL

## Files
| File | Description |
|------|-------------|
| `chinook_analysis.sql` | All SQL queries organised by concept |
| `chinook_analysis_report.docx` | Query explanations and business insights |

## SQL Concepts Covered
- **SELECT & WHERE** — Extracting and filtering data
- **ORDER BY** — Sorting results
- **GROUP BY & Aggregates** — Summarising data using COUNT, SUM, AVG
- **HAVING** — Filtering grouped results
- **INNER, LEFT & RIGHT JOINs** — Combining data across tables
- **Subqueries** — Nested queries for multi-level analysis
- **Window Functions** — RANK(), ROW_NUMBER(), PARTITION BY

## Business Questions Answered
- Who are the top 10 customers by total spending?
- Which countries generate the most revenue?
- What are the best-selling tracks and genres?
- What does the revenue trend look like over time?
- Which customers spend above average?
- Which tracks have never been purchased?

## Key Findings
- The **USA** is the top market with $523.06 in total revenue and 91 invoices
- Only **Canada and USA** have more than 5 customers each
- **Rock** is the dominant genre by track sales and revenue
- Many tracks in the catalogue have **zero sales**, presenting a promotion opportunity

## How to Run
1. Install MySQL Workbench
2. Download and run Chinook_MySql.sql from the Chinook GitHub repo to set up the database
3. Open chinook_analysis.sql in MySQL Workbench
4. Run each section using the execute button (⚡)
