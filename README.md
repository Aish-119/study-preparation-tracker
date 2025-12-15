# Study-Preparation-Tracker 

College and exam-aspiring students struggle to keep consistent track of study activities.
Existing manual methods lack structured tracking, progress summaries, and actionable insights.

## Solution
This project provides a backend API for students to log daily study activities.
It tracks streaks, gathers weekly performance summaries, and records study logs so learners can monitor consistency and identify weak spots. The system exposes REST endpoints for authentication, logging activities, and retrieving reports.

## Key Features 
1. JWT-based user registration and login
2. Daily study log creation and retrieval
3. Tracking and reporting of study streaks
4. Weekly performance summaries via API
5. SQLite database (with future move to PostgreSQL)


## Tech Stack 
1. Python 3.10+
2.  FastAPI
3.  SQLite (initial)
4. SQLAlchemy
5. JWT Authentication
6. Uvicorn


## Future Improvements 
Looking forward to add as many AI stacks and technologies which makes the learning journey progressive and to make learning a thoughtful, an interesting experience to students.
1. *Add analytics for weak topic detection*
2. *Deploy on cloud with CI/CD*
3.  *Add frontend interface*
4.   *Use ML for personalized study suggestions*
