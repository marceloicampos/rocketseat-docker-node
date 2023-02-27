# Use Docker file

```docker build -t marceloic/dockernodejs .```

> after build run docker

```docker run -p 3000:3000 -d marceloic/dockernodejs```

> open browser on http://localhost:3000/

# Use Docker compose

> install nodemon

```npm install nodemon```

> change npm script on package.json
- "start": "node index.js" TO "start": "nodemon index.js"

> run docker compose up
```docker-compose up```
