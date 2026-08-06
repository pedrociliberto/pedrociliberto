<div align="center">

# Hi there! I'm Pedro Ciliberto.

I'm a 4th year student pursuing a **Software Engineering** Undergraduate Degree, at Buenos Aires University (FIUBA). 

Teaching Assistant for 2 programming subjects at FIUBA.

</div>

## 🛠️ My tools

#### Infraestructure

![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)

#### Languages

- **Advanced / Actively used**

![Bash Script](https://img.shields.io/badge/bash_script-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white)
![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white)
![CSS](https://img.shields.io/badge/css-%23663399.svg?style=for-the-badge&logo=css&logoColor=white)
![Go](https://img.shields.io/badge/go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Markdown](https://img.shields.io/badge/markdown-%23000000.svg?style=for-the-badge&logo=markdown&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Rust](https://img.shields.io/badge/rust-%23000000.svg?style=for-the-badge&logo=rust&logoColor=white)

- **Worked on**

![AssemblyScript](https://img.shields.io/badge/assembly%20script-%23000000.svg?style=for-the-badge&logo=assemblyscript&logoColor=white)
![Clojure](https://img.shields.io/badge/Clojure-%23Clojure.svg?style=for-the-badge&logo=Clojure&logoColor=Clojure)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![Kotlin](https://img.shields.io/badge/kotlin-%237F52FF.svg?style=for-the-badge&logo=kotlin&logoColor=white)
![Octave](https://img.shields.io/badge/OCTAVE-darkblue?style=for-the-badge&logo=octave&logoColor=fcd683)
![Ruby](https://img.shields.io/badge/ruby-%23CC342D.svg?style=for-the-badge&logo=ruby&logoColor=white)

#### Databases

![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![Neo4J](https://img.shields.io/badge/Neo4j-008CC1?style=for-the-badge&logo=neo4j&logoColor=white)
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)

#### Data Science, Machine & Deep Learning Frameworks

![Apache Spark](https://img.shields.io/badge/Apache%20Spark-FDEE21?style=flat-square&logo=apachespark&logoColor=black)
![Keras](https://img.shields.io/badge/Keras-D00000.svg?style=for-the-badge&logo=keras&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=%white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=tensorflow&logoColor=white)

#### Backend

![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/sqlalchemy-%23D71F00.svg?style=for-the-badge&logo=sqlalchemy&logoColor=white)

#### IDEs & Editors

![Android Studio](https://img.shields.io/badge/Android%20Studio-3DDC84.svg?style=for-the-badge&logo=android-studio&logoColor=white)
![IntelliJ IDEA](https://img.shields.io/badge/IntelliJIDEA-000000.svg?style=for-the-badge&logo=intellij-idea&logoColor=white)
![Obsidian](https://img.shields.io/badge/Obsidian-%23483699.svg?style=for-the-badge&logo=obsidian&logoColor=white)
![PyCharm](https://img.shields.io/badge/pycharm-143?style=for-the-badge&logo=pycharm&logoColor=black&color=black&labelColor=green)
![RubyMine](https://img.shields.io/badge/RubyMine-%23000000.svg?style=for-the-badge&logo=RubyMine&logoColor=white)

## 📝 Projects I've worked on

### 🎾 The Tennis World - [Match Predictions](https://github.com/pedrociliberto/CienciaDeDatos-2026C1/blob/main/tps/tp2.ipynb) & [Exploratory Analysis Queries](https://github.com/pedrociliberto/CienciaDeDatos-2026C1/blob/main/tps/tp1.ipynb)

The goal of this project was to build a machine learning pipeline to **predict professional ATP tennis match winners** based on pre-match historical statistics, ensuring strict data leakage prevention and class symmetry through random player assignments. By a process of Feature Engineering, I created special feature differences, such as adjusted ELO ratings, recent match streaks, and surface-specific performances. The project evaluated linear and non-linear approaches, ultimately achieving a performance boost from a baseline 67% accuracy using Logistic Regression to a top **80% accuracy and F1-score using an optimized XGBoost model**. 

Previous to this work, I chose a big ATP big tennis dataset found in [Kagle](https://www.kaggle.com/datasets/warcoder/atp-tennis-rankings-results-and-stats1968-2023), narrowing the scope to ATP Tour singles matches from 1990 to 2023 to align with my personal tennis knowledge. I set up key Python libraries including `pandas`, `matplotlib`, `seaborn`, `numpy`, `networkx`, and `re`, and dynamically loaded and concatenated the yearly files into three core DataFrames: `matches`, `rankings`, and `players`. I mainly used **Pandas and Spark queries** to find information because they provided a fast, scalable way to query, filter, and process large multi-year datasets.


### 🧉 [Hang-Out](https://github.com/pedrociliberto/Gestion-2026C1/tree/main/Hang-Out) - Meeting Planner

Hang-Out is an application developed for managing group gatherings and meeting events, designed to unify social organization and coordination in one same place. Within the app, users can set up custom gatherings or large events with specified dates, times, and locations (including open businesses) invite participants, and vote the best and most suitable option for the group.

## 👨‍💻 Top Languages

[![Top Langs](https://github-stats-extended.vercel.app/api/top-langs/?username=pedrociliberto&count_private=true&langs_count=10&layout=compact&theme=dark&hide=Jupyter%20Notebook)](https://github.com/anuraghazra/github-readme-stats)
