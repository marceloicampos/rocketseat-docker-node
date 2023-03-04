# Node JS with Docker

## Use Docker file

#### npm install

```npm install```

#### change npm script on package.json
"start": "nodemon index.js" TO "start": "node index.js"

#### docker build

```docker build -t marceloic/dockernodejs .```

#### after build use docker run

```docker run -p 3000:3000 --name="dockernodejs" -d marceloic/dockernodejs```

#### open browser on 
http://localhost:3000/

#### after user docker stop

```docker stop hash_of_my_container```

## Use Docker compose

#### npm install

```npm install```

#### change npm script on package.json
"start": "node index.js" TO "start": "nodemon index.js"

#### run docker compose up

```docker-compose up```

#### open browser on 
http://localhost:3000/

#### after user docker stop

```docker stop hash_of_my_container```
