
# docker and kubernetes the complete guide

https://www.udemy.com/docker-and-kubernetes-the-complete-guide

## Run dev

In the project directory, you can run:

#### `docker-compose up`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

## Run production

#### `docker build -t frontend_production .`
#### `docker run -p 8080:80 frontend_production`

Open [http://localhost:8080](http://localhost:8080) to view it in the browser.

