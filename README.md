# graphql-samples

Getting Started
---

```sh
git clone https://github.com/asishpmathew/graphql-node-samples.git 
cd graphql-example
npm install
npm run dev
```
You should be able to see the app running at http://localhost:3000.

Information
---
Information
-The models folder contains the three models: User, Project and Task. They are created using the sequelize ORM.
-The rest folder contains the logic to create the associated /api/users, /api/projects and /api/tasks endpoints.
-The graphql folder contains the schema and resolvers for GraphQL.
-db.sqlite contains the database.
-index.js starts the Express server.

Demo
---
-This example project is hosted on Heroku.

-The rest endpoints can be viewed here

```sh
  1. http://localost/api/users
  2. http://localost/api/projects
  3. http://localost/api/tasks
  ```
