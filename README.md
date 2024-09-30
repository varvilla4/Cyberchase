# Cyberchase Episode Database
## Project Overview
Cyberchase is an educational TV series aired on PBS since 2002, teaching kids math, science, and problem-solving skills. In this project, you’ll explore the cyberchase.db database, which contains information about Cyberchase episodes, including their titles, seasons, topics, air dates, and more. Using SQL queries, you will answer various questions related to the show’s episodes, such as listing episode titles, finding production codes, and counting episodes from specific time periods.

## Problem Statement
The cyberchase.db database includes a table called episodes that stores detailed information about each episode of Cyberchase. Your goal is to write SQL queries that extract specific information from the database based on different prompts.

The queries will help answer questions about the show’s episode details, such as which episodes aired in the first season, the titles of episodes without topics, and how many episodes have been released in recent years.

## Database Structure
The episodes table in the cyberchase.db database contains the following columns:

 - id: A unique identifier for each episode.
 - season: The season number in which the episode aired.
 - episode_in_season: The episode’s number within the season.
 - title: The title of the episode.
 - topic: The educational topic the episode focuses on.
 - air_date: The date the episode aired (formatted as YYYY-MM-DD).
 - production_code: A unique code used by PBS to track the episode internally.
   
## Problem Specification
For this project, you will write SQL queries to answer the following questions:

 - Task 1: List the titles of all episodes from Season 1 of Cyberchase.
 - Task 2: List the season number and title of the first episode from each season.
 - Task 3: Find the production code for the episode titled "Hackerized!".
 - Task 4: List the titles of episodes that do not have a listed topic.
 - Task 5: Find the title of the holiday episode that aired on December 31st, 2004.
 - Task 6: List the titles of Season 6 episodes that were released early in 2007.
 - Task 7: List the titles and topics of episodes that teach the concept of fractions.
 - Task 8: Count the number of episodes released in the last 6 years, from 2018 to 2023.
 - Task 9: Count the number of episodes released in Cyberchase’s first 6 years, from 2002 to 2007.
 - Task 10: List the ids, titles, and production codes of all episodes, ordered by production code from earliest to latest.
 - Task 11: List the titles of episodes from Season 5 in reverse alphabetical order.
 - Task 12: Count the number of unique episode titles across all seasons.
 - Task 13: Write a custom query of your choice, including at least one condition using WHERE with AND or OR.
