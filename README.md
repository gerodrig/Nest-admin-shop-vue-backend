<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>


# Teslo API

1. Clone project
2. ```yarn install```
3. Clone file  ```.env.template``` and rename it to```.env```
4. Rename the environment variables in the ```.env``` file
5. Start the database with docker-compose
```
docker-compose up -d
```

6. start project: ```yarn start:dev```

7. Execute the following endpoint to seed the database
```
http://localhost:3000/api/seed
```



# Production notes:


