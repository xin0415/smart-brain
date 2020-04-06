# Smart-brain <br/>

This is a front end of smart-brain.

## Run the project 

### `clone this project`

### `run` npm install

### `run` npm start

## Run the entire project
To download smart-brain back-end server: [Smart-brain-server](https://github.com/xin0415/smart-brain-api)<br/>
Create your database: <br/>CREATE TABLE users(
						id serial PRIMARY KEY,
						name VARCHAR(100),
						email text UNIQUE NOT NULL,
						entries BIGINT DEFAULT 0,
						joined TIMESTAMP NOT NULL
					);<br/>
					CREATE TABLE login(
						id serial PRIMARY KEY,
						hash varchar(100) NOT NULL,
						email text UNIQUE NOT NULL
					);<br/>
Change the db variable in the file server.js to your database information