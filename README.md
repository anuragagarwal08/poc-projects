# poc-projects
#--------------------- Steps to develop node-express-postgres-sequalize/node-crud-api --------------------
#mkdir node-crud-api
#cd node-crud-api
#npm init -y
#npm i express pg sequelize
#	express is the Node.js framework
#	pg is a driver for a connection with a Postgres db
#	sequelize is the ORM so we avoid typing SQL queries
#mkdir controllers routes util models
#	Open the folder with your favorite IDE. If you have Visual Studio Code, you can type this from the terminal: code .
#Populate the util/database.js file
#Populate the models/user.js file
#Populate the controllers/users.js file
#Populate the routes/users.js file
#Populate the "index.js file"
#Create .dockerignore (it starts with a dot)
#Create Dockerfile (capital D)
#Create docker-compose.yml
#--------------------- Steps and commands to build and run the container --------------------
#docker compose up -d node_db
#docker compose logs
#docker compose build
#docker compose up -d node_app