# Ruby on Rails and Postgres image Docker

#### Versions
- Ruby = 2.6.6
- Rails >= 6.1.3
- Postgres = lasted

## Setup

Create your application directory and clone this repository. 
Run the following commands in your terminal within your directory: 

1. Build image

`sudo docker-compose build`

2. Create Ruby on Rails application
 
 `sudo docker-compose run --no-deps web rails new . --force --database=postgresql`
 
3. Run your application

`sudo docker-compose up`

### How to access image terminal?

`sudo docker exec -it <NAME DOCKER APP> /bin/bash`

### Attach application

`sudo docker attach <NAME DOCKER APP>`

### Get application name in Docker

`sudo docker ps` or `sudo docker stats`
