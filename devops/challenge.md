# DevOps Challenge

## What to do

1. Create a GitHub repository and an AWS project.
1. Implement a simple Node.js server which just serves the response `hello hokify` on `GET /`.
1. Implement a `Dockerfile` for that Node.js server.
1. Create a setup in AWS which allows to run the Docker image and expose the server at a publicly available URL.
1. Wire it up: Implement a GitHub Actions workflow which uses the `Dockerfile` to build the Docker image and deploys it to AWS.

## What to submit

Three things:

1. Link to the GitHub repository.
1. Link to the publicly available URL which returns `hello hokify`.
1. A description about the AWS infrastructure setup (which AWS services are in use, how is the network set up, ...).
