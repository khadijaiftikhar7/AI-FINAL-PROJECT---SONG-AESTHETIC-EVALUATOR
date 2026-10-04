Song Aesthetics Evaluator

A machine learning project that predicts how musical a song is from acoustic features extracted from its audio.

Built for an AI course project (Oct–Dec 2025).

Overview

The project asks whether audio features alone can predict how musical or aesthetically pleasing a song is. Several regression models are trained on the same feature set and compared on standard regression metrics.

Features used

Acoustic features extracted from each track, including:

Spectral centroid
Spectral bandwidth
Spectral flatness
Richness
 : list the remaining features
Models compared
 : e.g. Linear Regression, Random Forest, SVR, ...

Evaluated with  : e.g. MAE, RMSE, R².

Results

 : add a small table with each model and its metrics, plus one line on the best model.

Repository contents
File	What it is
AI Assignment 1 (code+report) (1).zip	Assignment 1 code and report
BaseLine_Model_ASGN2.zip	Baseline model (Assignment 2)
AI_FINAL_PROJECT.zip	Final project code and report

 : unzip these and commit the folders so the code is readable on GitHub without downloading.

How to run
bash
git clone https://github.com/khadijaiftikhar7/AI-FINAL-PROJECT---SONG-AESTHETIC-EVALUATOR.git
cd AI-FINAL-PROJECT---SONG-AESTHETIC-EVALUATOR
pip install -r requirements.txt   #  : add a requirements.txt (pip freeze, or list pandas, scikit-learn, librosa, ...)
python main.py                    #  : or "open <notebook>.ipynb"
Dataset

 : where the audio feature dataset came from and how it is loaded.

License

MIT

=== README for: Disaster Management System (new repo, suggested name: disaster-management-system) ===

Disaster Management & Relief Coordination System

A database-backed web application for coordinating disaster response: victims, volunteers, teams, zones, resources and relief requests.

Built as a semester team project (Feb–May 2025).

Overview

During a disaster, the hard part is matching needs to help. This system keeps victims, volunteers, response teams, affected zones, resources and relief requests in one structured database, and gives coordinators interfaces to see and manage them.

Tech stack
Java, Spring Boot
Thymeleaf (server-rendered pages)
 : database (e.g. MySQL / PostgreSQL / H2)
Data model

The main entities and how they relate:

Users
Victims
Volunteers
Teams
Zones
Resources
Requests

 : add an ER diagram image, or one line per relationship (e.g. a team belongs to a zone, a request is assigned to a team).

Features
 : e.g. register victims and volunteers
 : e.g. create and assign relief requests
 : e.g. track resource availability by zone
How to run

Requirements: JDK   (17?), Maven (or use the included wrapper), and   database.

bash
git clone <repo-url>
cd disaster-management-system
# 1. Create the database and set credentials in src/main/resources/application.properties
# 2. Run:
./mvnw spring-boot:run

Then open http://localhost:8080 (default Spring Boot port).

My contribution
Application structure and database design
Relationships between users, victims, volunteers, teams, resources and requests
Interfaces for coordinating response information
License

MIT

