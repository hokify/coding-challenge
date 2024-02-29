# DevOps Challenge

## What to do

1. Create a GitHub repository and an AWS project.
1. Implement a Node.js server which serves the response `hello hokify` on `GET /` using [Express](https://expressjs.com/) in TypeScript.
1. Implement a `Dockerfile` for that Node.js server.
1. Create a setup in AWS which allows to run the Docker image and expose the server at a publicly available URL.
1. Wire it up: Implement a GitHub Actions workflow which uses the `Dockerfile` to build the Docker image and deploys it to AWS.
1. Document your workflow, thoughts and challenges in a `README.md` in the repository.

> ℹ️ GitHub Free and AWS Free Tier should cover everything, so no costs should occur!

## What to consider

- Apply Best Practices for each part of the challenge.

## What to submit

Three things:

1. Link to the GitHub repository.
1. Link to the publicly available URL which returns `hello hokify`.
1. A description about the AWS infrastructure setup (which AWS services are in use, how is the network set up, ...).
