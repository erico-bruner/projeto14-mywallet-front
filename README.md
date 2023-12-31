# Overview

This project is a backend application of an activity proposed by @Driven. In this application it is possible to manage the front-end of an expense and income system.

# Demo

https://mywallet-blond.vercel.app/

# How it works?

This project is a REST API to serve the application of a betting website. It has three entities: `game`, `participant` and `bet`. The characteristics of these entities are in the `schema.prisma` file.

# Technologies

For this project, the following were used:

- React (v 18.2.0);
- Styled-components;
- Axios;

# How to run in development

- Clone this repository
- Install all dependencies

  ```bash
  npm i
  ```

- Configure the `.env` file using the `.env.example` file (see "Running the application locally or within the docker section" for details), if you wish you can use an API that was developed together with this application (https://mywallet-api-rgbt.onrender.com)

- Run the back-end in a development environment:

  ```bash
  npm run dev
  ```

# How to run in Docker environment

Note: You must have Docker installed

- Clone this repository
- Install all dependencies

  ```bash
  npm i
  ```

- Configure the `.env` file using the `.env.example` file (see "Running the application locally or within the docker section" for details), if you wish you can use an API that was developed together with this application (https://mywallet-api-rgbt.onrender.com)

- Using docker commands, build the image

  ```bash
  docker build -t MYNAMEIMAGE .
  ```

- Now you can upload your created container!

  ```bash
  docker run -d --name MYFRONT-END -p 8080:80 MYNAMEIMAGE
  ```

# How to run in Docker environment with provided image

Note: You must have Docker installed

- Just use the command below to download and upload the container!

  ```bash
  docker run -d -p 8080:80 --name MYFRONT-END ericobruner/mywallet-front
  ```
