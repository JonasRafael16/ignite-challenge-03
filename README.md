# 💻 Description

This application performs the CRUD (Create, Read, Update, Delete) of project repositories. In addition, it is possible to give likes to registered repositories, increasing the number of likes by 1 each time the route is called.

- Create a new repository with title, url, techs and likes
- List all repositories;
- Change the title, url and techs of an existing repository;
- Like an existing repository;
- Delete a repository;

- GET /repositories → list of all repositories.
- POST /repositories → create a repository.
- PUT /repositories/:id → updates a repository.
- POST /repositories/:id/like → adds a like to a repository.
- DELETE /repositories/:id → delete a repository by id

Use
With the dependencies installed, I ran yarn dev to upload the server. To run the tests, run yarn test.

*In this challenge, I used the knowledge acquired to locate and correct errors in the code.*