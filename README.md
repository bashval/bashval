# Valentin Bashkatov

## 🚀 About Me

Hi there! I'm a beginner software developer with a passion for learning and building real-world applications. I'm currently focusing on Python and expanding my skills in asynchrony (`FastAPI`, `aiogram`).


## 🛠️ Tech Stack

**Languages**  
![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=yellow)
![SQL](https://img.shields.io/badge/-SQL-003B57)
![HTML5](https://img.shields.io/badge/-HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/-CSS3-1572B6?logo=css3&logoColor=white)

**Frameworks & Libraries**  
![Django](https://img.shields.io/badge/-Django-092E20?logo=django&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?logo=fastapi)
![DRF](https://img.shields.io/badge/-DRF%20(Django%20REST)-8C1D40?logo=django&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-768776?logo=sqlalchemy&logoColor=D71F00)
![pydantic](https://img.shields.io/badge/pydantic-E92063?logo=pydantic)
![Aiogram](https://img.shields.io/badge/-Aiogram-2CA5E0?logo=telegram&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?logo=flask)
![Pandas](https://img.shields.io/badge/Pandas-150458?slogo=pandas)
![Numpy](https://img.shields.io/badge/Numpy-013243?logo=numpy)
![Pytest](https://img.shields.io/badge/-Pytest-0A9EDC?logo=pytest&logoColor=white)
![unittest](https://img.shields.io/badge/-unittest-3776AB?logo=python&logoColor=white)

**Databases**  
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/-SQLite-003B57?logo=sqlite&logoColor=white)

**DevOps & Infrastructure**  
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?logo=nginx&logoColor=white)
![Docker-compose](https://img.shields.io/badge/Docker_compose-2496ED?logo=docker&logoColor=white)
![Gunicorn](https://img.shields.io/badge/gunicorn-%298729.svg?logo=gunicorn&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=flat&logo=Celery&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat&logo=Redis&logoColor=white)

**Tools**  
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?logo=postman&logoColor=white)
![DBeaver](https://img.shields.io/badge/DBeaver-382923?logo=dbeaver&logoColor=white)
![pgAdmin](https://img.shields.io/badge/pgAdmin-4169E1?logo=postgresql&logoColor=white)


## 🔥 My Projects:


- [**IHearYou Bot (FastAPI + aiogram) (Team project)**](https://github.com/Shpindik/Ihearyou_bot)  
  ▸ Telegram Bot providing information for families with children with hearing impairments.
  ▸ Designed and implemented a FastAPI-based backend with REST API endpoints and admin panel for content management and user interaction   
  ▸ Created database models and migrations using SQLAlchemy / Alembic, targeting PostgreSQL as the persistence layer  
  ▸ Integrated caching / auxiliary data storage with Redis for performance or session/data caching use cases  
  ▸ Developed and exposed authentication and authorization logic (JWT tokens, password hashing) for admin operations and secured API access  
  ▸ Coordinated with the Telegram bot component (built with aiogram) and frontend (React) via well-defined API contracts  
  ▸ Implemented key domain features:  
  - Hierarchical content navigation and keyword-based search over articles, videos, PDFs
  - User feedback (e.g. content rating), tracking, and analytics for improving content delivery  
  - Scheduled reminders to engage dormant users (every ~10 days)

  ▸ Containerized services with Docker / Docker Compose and provided project orchestration & setup via Makefile scripts  
  ▸ Applied test-driven practices (via pytest) and code quality tooling (e.g. formatting, linters) to ensure maintainability 
GitHub   

- [**Cookbook (Django REST Framework + Deployment)**](https://github.com/bashval/cookbook)  
  ▸ REST API backend for SPA of cooking recepies site  
  ▸ Available to print cumulative ingredients list of all recipes in cart in PDF  
  ▸ Containerized with Docker (PostgreSQL, Nginx, backend, frontend)  
  ▸ CI/CD pipeline with GitHub Actions (automatic testing and deployment)  
  ▸ Configured Nginx as reverse proxy for backend/frontend  
  ▸ Implemented Docker volumes for static/media files and database persistence 

- [**YaMDb API (Django REST Framework) (Team project)**](https://github.com/bashval/api_yamdb)  
  ▸ REST API for review platform of books/movies/music  
  ▸ User authentication implemented using JWT token with data verification and password reset via email  
  ▸ Complex database relationships with cascade deletion  
  ▸ Complex serialization with nested serializers   
  ▸ Data import from CSV file using custom management-command

- [**Charity Fund Service (FastAPI)**](https://github.com/bashval/charity_fund_service)  
  ▸ The project is implemented as an API using the FastAPI framework.  
  ▸ User authentication using JWT  
  ▸ Implemented donation logic:
    - Administrator (superuser) can create and edit charity projects for various purposes, specifying the required amount.
    - Regular users can make donations and add comments.
    - Each donation is automatically allocated to the first open project that has not yet reached its funding goal.
    - If a donation exceeds the required amount, or if there are no open projects, the remaining funds are kept until a new project is opened.
    - When a new project is created, all unallocated donations are automatically invested in it.

  ▸ Charity projects reports generation to Google Sheets using Google API.

- [**Blogicum Platform (Django)**](https://github.com/bashval/django_sprint4)  
  ▸ User Management: registration, authentication, and profile customization  
  ▸ Technical Features: custom error pages, pagination for posts and comments, email notification system  
  ▸ Content Management: create, edit, and delete posts; upload and display post images; add/remove comments  


### ⚡Stats

![Profile Summary](http://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=bashval&theme=vue)


#### Codewars profile

[![codewars](https://www.codewars.com/users/bashval/badges/large?theme=light)](https://www.codewars.com/users/bashval)


### 📫 Follow me

[![Telegram](https://img.shields.io/badge/-Telegram-26A5E4?style=flat&logo=Telegram&logoColor=white)](https://t.me/kraffc)
[![Email](https://img.shields.io/badge/-Email-D14836?style=flat&logo=Gmail&logoColor=white)](mailto:jard.mozq@gmail.com)
[![linkedin](https://img.shields.io/badge/LinkedIn-0075B5?&style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/valentin-bashkatov/)
[![GitHub](https://img.shields.io/badge/github-%23404040?&style=flat&logo=github&logoColor=white)](https://github.com/bashval)
