# What is Docker Compose 
Docker Compose is a tool for management of multi container applications by allowing you to define and run them using a single YAML file. Instead of manually starting each container with docker run commands manually, you can use a single command, ``docker compose up``, to running the entire application stack. This approach streamlines the development workflow, making it easier to manage complex microservice architectures.

# Why Docker Compose
If you don't use Docker Compose, you'll need to manually start and manage each container using separate docker run commands. This can be time consuming especially for projects with multiple services, as you'll have to handle networking, environment variables, and dependencies yourself. Docker Compose simplifies this by letting you define and manage everything in a single YAML file and start all services with one command.

