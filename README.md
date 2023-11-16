# Node.js Docker Optimisation Project

## Introduction

A Node.js application optimised for Docker containerisation, focusing on production efficiency and security. The project demonstrates best practices in creating Docker images specifically tailored for Node.js applications. 


## Requirements

Before you begin, ensure you have the following prerequisites installed:

- [Node.js](https://nodejs.org/en/) and [npm](https://www.npmjs.com/get-npm) installed.
- [Docker](https://www.docker.com/get-started) installed.


### Installation

1. Clone the repository locally:

   ```bash
   git clone https://github.com/Zhagi/Docker-Multi-Stage-Project.git
   cd your-repo

  ## Usage

2. To build the Docker image and access the application in your web browser at http://localhost:3000, run the following commands:

npm install
docker build -t yourapp .
docker run -p 3000:3000 yourapp


3. To test the application, run the following commands:

npm run build
npm start

Navigate to http://localhost:3000 to verify if your application is running correctly.