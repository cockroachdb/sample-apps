# 📖 Contents

- [Hello, World!](#hello-world)
- [CockroachDB in action](#cockroachdb-in-action)
- [Hackathon Hall of Fame](hackathon-hall-of-fame)


# 👋 Hello, World!

CockroachDB's wonderful Docs team maintains a repository of simple but complete example applications for each supported language and library combination. Following are some of the popular example apps: 

## JavaScript/TypeScript

| Driver/ORM Framework                                    | Support level  | Example apps                                           |
|---------------------------------------------------------|----------------|--------------------------------------------------------|
| [pg](https://www.npmjs.com/package/pg)                  | Full           | [Simple CRUD](build-a-nodejs-app-with-cockroachdb.html)
| [Sequelize](https://www.npmjs.com/package/sequelize)    | Full           | [Simple CRUD](build-a-nodejs-app-with-cockroachdb-sequelize.html)
| [TypeORM](https://www.npmjs.com/package/typeorm)        | Full           | [Simple CRUD](build-a-typescript-app-with-cockroachdb.html)

## Python

| Driver/ORM Framework                                            | Support level  | Example apps                                           |
|-----------------------------------------------------------------|----------------|--------------------------------------------------------|
| [psycopg2](https://www.psycopg.org/docs/install.html)           | Full           | [Simple CRUD](build-a-python-app-with-cockroachdb.html)
| [SQLAlchemy](https://www.sqlalchemy.org/)                       | Full           | [Hello World](hello-world-python-sqlalchemy.html)<br>[Simple CRUD](build-a-python-app-with-cockroachdb-sqlalchemy.html)<br>[MovR-Flask (Global Web App)](movr-flask-overview.html)
| [Django](https://pypi.org/project/Django/)                      | Full           | [Simple CRUD](build-a-python-app-with-cockroachdb-django.html)
| [PonyORM](https://ponyorm.org/)                                 | Full           | [Simple CRUD](build-a-python-app-with-cockroachdb-pony.html)

## Java

| Driver/ORM Framework                       | Support level  | Example apps                                            |
|--------------------------------------------|----------------|--------------------------------------------------------|
| [JDBC](https://jdbc.postgresql.org/)       | Full           | [Hello World](hello-world-java-jdbc.html)<br>[Simple CRUD](build-a-java-app-with-cockroachdb.html)<br>[Roach Data (Spring Boot App)](build-a-spring-app-with-cockroachdb-jdbc.html)
| [Hibernate](https://hibernate.org/orm/)    | Full           | [Simple CRUD](build-a-java-app-with-cockroachdb-hibernate.html)<br>[Roach Data (Spring Boot App)](build-a-spring-app-with-cockroachdb-jpa.html)
| [jOOQ](https://www.jooq.org/)              | Full           | [Simple CRUD](build-a-java-app-with-cockroachdb-jooq.html)

## Ruby

| Driver/ORM Framework                                      | Support level  | Example apps                                            |
|-----------------------------------------------------------|----------------|--------------------------------------------------------|
| [pg](https://rubygems.org/gems/pg)                        | Full           | [Simple CRUD](build-a-ruby-app-with-cockroachdb.html)
| [ActiveRecord](https://rubygems.org/gems/activerecord)    | Full           | [Simple CRUD](build-a-ruby-app-with-cockroachdb-activerecord.html)

For the complete list of apps, see [CockroachDB Example Apps](https://www.cockroachlabs.com/docs/stable/example-apps.html)

# 🚀 CockroachDB in action

Following are full-stack, functional applications built by Roachers and contributors to demonstrate CockroachDB features:

App | CockroachDB feature | Description | Tech Stack | GitHub Repo / Blog Post |  
----|----------|-------------|------------|-------------|
Dad Jokes! | Multi-region | A quick tutorial on how to create, develop, and test multi-region CockroachDB applications on your local desktop. | CockroachDB, SQL | https://github.com/chriscasano/multi-region-dad-jokes | 
Geo-tourist | Spatial | Use the spatial features in CockroachDB to find pubs, restaurants, cafes, etc. | CockroachDB, Python Flask, Javascript, Kubernetes | https://github.com/cockroachlabs-field/crdb-geo-tourist
MovR | Multi-region | Use the multi-region features of CockroachDB to build a functional vehicle-sharing app. | CockroachDB, Python, SQLAlchemy | https://github.com/cockroachdb/movr
Node.js application | Basic CRUD operations | The source code for a simple full-stack CRUD application, written in Node.js. The application uses Sequelize to connect to and communicate with a free CockroachCloud cluster. | CockroachCloud, Node.js, Sequelize Pug templates, Heroku | https://github.com/cockroachdb/fullstack-node-cockroachdb-app https://www.cockroachlabs.com/blog/full-stack-node-app/| 

# 🥇 Hackathon Hall of Fame

The amazing CockroachDB apps that hackathon participants build over just one weekend never cease to amaze us.

Hackathon | App | Description | Tech Stack | Use Case | GitHub Repo / DevPost Link
----------|-----|-------------|------------|----------|----------------------------
Hack the North 2020++ | Flock | Right swipe on films you are interested in watching, match films with friends and flock together | React-native, Expo, React-native-paper, CockroachDB, Google App Engine, Express.js | Social Networking Platform | [GitHub Repo](https://github.com/SPriyaJain/movie-night-htn) [DevPost](https://devpost.com/software/flock-figure-out-what-film-to-watch-with-friends)
cmd-f | FinWhiz | A data-first approach to simplifying finance and investment. | CockroachDB, GCP, pyscopg2, SQLAlchemy, Streamlit, Plotly, nltk (Natural Language Processing library) | FinTech | [GitHub Repo](https://github.com/liuhh02/FinWhiz) [DevPost](https://devpost.com/software/finwhiz-5908hk)
HackOR | Sundial | A web app for yoga teachers and students to algorithmically generate yoga sequences. | Python, Flask, CockroachDB, JavaScript, JSX, HTML, CSS, React, Bootstrap | Health and Wellness | [GitHub Repo](https://github.com/yvonneyeh/HackOR-Lovelace-Ladies) [DevPost](https://devpost.com/software/sundial-mcfi7l)
TOHacks | vagon.tech | Empowering sustainable & equitable distributed transportation at scale | Vue.js, Nuxt.js, Golang, Gin, Google Firebase, CockroachDB, Google Cloud, Docker, Google Cloud Run | Logistics Platform | [GitHub Repo](https://github.com/TOHacks-Team-Alpha) [DevPost](https://devpost.com/software/vagon-tech)

