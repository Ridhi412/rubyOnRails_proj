# rubyOnRails_proj

Dan Wahlin, Docker dev said - "Docker can help there because we can make one or more images that can then be converted into running containers, and those containers can run on our different developer, and even designer machines."

Steps to follow, to create project from scratch -

Installing Docker and including Ignorefiles
- Install Docker
- Make a .dockerignore file

Dockerfile and docker-compose file
- Make a file 'Dockerfile'
- Make a file 'docker-compose.yml'

Building and running the container
- Run docker-compose build
- Run docker-compose run --rm --service-ports ruby_dev

Test-run rails app
- Run rails new myapp && cd myapp
- Run bundle update && bundle install
- Test the server by running rails server -p $PORT -b 0.0.0.0

Cleaning up
- Run docker-compose down
