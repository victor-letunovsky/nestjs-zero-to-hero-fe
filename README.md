# Task Management Application Front-end

This application acts as the front-end for the Task Management application developed throughout the
*[NestJS - Zero to Hero](https://gitlab.com/learn-courses/udemy/nestjs-zero-to-hero)* course, produced by Ariel Weinberger.

[Original repo](https://github.com/arielweinberger/task-management-frontend)

# Setup and Run

Install dependencies:
```bash
yarn
```

Start application:
```bash
yarn start
```

Open URL `http://localhost:3001/signin`

# Deploy to GitHub pages
* Go to repo "Settings -> Secrets and variables -> Actions -> New repository secret"
* Define two secret variables
  1. `REACT_APP_BASE_URL` should be URL from [Heroku back-end app deployment](https://nestjs-zero-to-hero-51c8f28b1c34.herokuapp.com).
  2. `PUBLIC_URL` should be GitHub pages URL https://victor-letunovsky.github.io/nestjs-zero-to-hero-fe .
* Go to repo "Actions -> All workflows -> Deploy" and "Run workflow" on `main` branch.
* Go to repo "Settings -> Pages" and deploy `gh-pages` branch.
