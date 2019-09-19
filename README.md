# A React + Apollo + GraphQL GitHub Client
I am learning SO MUCH from [this guy!](https://github.com/the-road-to-graphql) Please check out his repos and his [blog, courses, and free tutorials.](https://www.robinwieruch.de/react-with-graphql-tutorial) His writing is excellent, very detailed, lots of code snippets, and he always provides links to the repos so you can get the finished app when you're ready to give up 😂

## Features

* React 16 with create-react-app
* Responsive
* React Router 4
* Apollo with GitHub GraphQL API
  * Queries and Mutations with render props
  * Optimistic Updates
  * Pagination
  * Optimistic Fetch (e.g. Issues)
    * not everywhere for the purpose of demonstrating though

## Installation

* `git clone git@github.com:the-road-to-graphql/react-graphql-github-apollo.git` (the original)
* `git clone https://github.com/I-keep-trying/react-graphql-github-apollo.git` (mine, I let npm fix a couple of issues)
* cd react-graphql-github-apollo
* add your own [GitHub personal access token](https://help.github.com/articles/creating-a-personal-access-token-for-the-command-line/) in a .env file in your root folder
  * scopes/permissions you need to check: admin:org, repo, user, notifications
  * REACT_APP_GITHUB_PERSONAL_ACCESS_TOKEN=xxxXXX
* npm install
* npm start
* visit `http://localhost:3000`