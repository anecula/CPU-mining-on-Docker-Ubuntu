# CPU-mining-on-Docker-Ubuntu
CPU mining on Ubuntu 14 or higher  using Docker


[![Docker]( https://img.shields.io/travis/rust-lang/rust.svg?organization=anecula&repository=CPU-mining-on-Docker-Ubuntu)](https://hub.docker.com/r/anecula/CPU-mining-on-Docker-Ubuntu/builds)

Before you start mining with Docker, you need to install it:
- [Install Docker] (https://docs.docker.com/engine/installation/)
- [Install Docker Compose] (https://docs.docker.com/compose/install/)

## Sign in a pool

 For this example I create an account on [minergate.com](https://minergate.com/) [feel free to use whatever pool you choose)
 
# Start mining in 2 minutes

1. Download the docker-compose.yml file  

`wget https://raw.githubusercontent.com/anecula/CPU-mining-on-Docker-Ubuntu/master/docker-compose.yml`

2. Run command: `docker-compose up -d`
3. See your container with: `docker ps`

If everything worked as expected and you can see your container Healthy/up and running go on Minegrad site and check your Dashboard (https://minergate.com/internal)


