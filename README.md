# Docker
TechWorld with Nana [Docker Crash Course for Absolute Beginners [NEW](https://www.youtube.com/watch?v=pg19Z8LL06w)

## What is Docker
- Virtualization software
- Makes developing and deploying applications much easier
- Packages application with all necessary dependencies, configuration, system tools and runtime
- Easily shared and distributed

## How did this work containers 
- every developer will need to install all packages and configuration needed to run their machine
- This is tedious

## Development process with containers 
- containers are in an isolated environment
- it will be same across operating systems
- the deployment and development part is packaged into the docker container

## Deployment process before containers
- Jar file for java for example
- Dependencies conflicts

## Virtual Machine VS Docker 
How is OS made up? there is the application layer and OS kernel
  - kernel is the middleman between application layer and hardware

Docker
- virtualizes the application layer of the OS and the services and apps installed on top of that layer
- Uses kernel of host

Virtual Machines 
- doesn't use the host kernel
- It virtualizes the application layer and OS kernel 

- Advantages of Docker
  - size of docker images is smaller so faster
  - Docker desktop is for windows and mac to run linux containers using a hypervisor 

- Disadvantages of Docker
  - not possible to run a linux docker image on a windows kernel
 
## Images and container 
- image is an executable application artifact
- Container is an running instance of an image

### Image Versioning 
a new docker image is created using tags in the docker hub website 

## Docker Registry
- dockerhub: storage of docker images

## Ports 


