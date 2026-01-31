# innomatics-genai-entrance-test
# Innomatics Research Labs – Advanced GenAI Internship Entrance Test

## Objective
Combine CSV, JSON, and SQL datasets into a single analytical dataset and answer business questions.

## Files Used
- orders.csv (Transactional data)
- users.json (User master data)
- restaurants.sql (Restaurant master data)

## Process
1. Loaded CSV using pandas
2. Loaded JSON using pandas
3. Executed SQL script using SQLite
4. Performed LEFT JOINs on user_id and restaurant_id
5. Generated final_food_delivery_dataset.csv

## Output
- final_food_delivery_dataset.csv (Source of truth for analysis)

## Tools
- Python
- Pandas
- SQLite
- Jupyter Notebook
