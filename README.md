# ETL - Side Project

A simple ETL (Extract Transform Load) pipeline. The project is a simple demonstration of how to:
* Extract data via an API
* Apply data transformations using Pandas
* Load data into MySQL using SQLAlchemy
* Build a dashboard web application using Dash and Plotly.
* Containerize the entire ETL pipeline using Docker.

# Technologies used to build the project

Python, SQLAlchemy, Pandas, Dash, Plotly, MySQL, Docker

# Running the application

Step 1: Simply change directory to `app` directory in the `project directory`.

```Shell
cd path_to_project_directory/app
```

Step 2: Build the app image

```Shell
docker build -t etl-app:latest .
```

Step 3: Start Docker Compose

```Shell
docker compose up -d
```

 Step 4: Open The web app
 
```Shell
localhost:3000
```
