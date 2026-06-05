# 🎬 Netflix Data Analysis — Advanced SQL Project

A structured SQL-based analysis of Netflix's content library, solving 15 real-world business problems using PostgreSQL.

## 📌 Objective
To explore, query, and extract meaningful insights from Netflix's dataset by applying advanced SQL techniques — simulating the kind of analysis a data analyst would perform on the job.

## 🗂️ Dataset Overview
| Column | Description |
|---|---|
| show_id | Unique ID for each title |
| type | Movie or TV Show |
| title | Name of the content |
| director | Director(s) |
| casts | Cast members |
| country | Country of production |
| date_added | Date added to Netflix |
| release_year | Year of release |
| rating | Content rating (PG, R, etc.) |
| duration | Duration in mins or seasons |
| listed_in | Genre(s) |
| description | Short synopsis |

## 🔍 Business Problems Solved
1. Count of Movies vs TV Shows
2. Most common rating per content type
3. Movies released in a specific year
4. Top 5 countries with the most Netflix content
5. Longest movie on Netflix
6. Content added in the last 5 years
7. All content by director 'Rajiv Chilaka'
8. TV Shows with more than 5 seasons
9. Item count by genre
10. Top 5 years with highest avg content release in India
11. All documentary movies
12. Content with missing director info
13. Salman Khan movies in the last 10 years
14. Top 10 actors in Indian-produced content
15. Content categorized as 'Good' or 'Bad' based on description keywords

## 🛠️ SQL Concepts Used
- **Window Functions** — `RANK()`, `PARTITION BY`
- **String Functions** — `UNNEST`, `STRING_TO_ARRAY`, `SPLIT_PART`, `ILIKE`
- **Date Functions** — `TO_DATE`, `EXTRACT`, `INTERVAL`
- **Subqueries & Nested Queries**
- **CASE WHEN** for conditional categorization
- **Aggregate Functions** with `GROUP BY`

## 🚀 How to Run
```sql
-- 1. Create the table
CREATE TABLE netflix ( ... );

-- 2. Load the dataset into the table

-- 3. Run any query from netflix_analysis.sql
```

## 📁 Files
```
📦 netflix-sql-analysis
 ┣ 📄 netflix_analysis.sql   -- All 15 business problem queries
 ┣ 📄 schema.sql             -- Table creation script
 ┗ 📄 README.md
```

## 🙋 About
Built as a portfolio project to strengthen SQL skills for data analyst roles.
