# What is a Container ?

* Standardized, portable packaging for your applications.
* A container is a standard unit of software that packages up code and all its dependencies so the application runs quickly and reliably from one computing   environment to another.
* Bundlesan application's code together with the related configuration files and libraries, and with the dependencies required for the app to run.
* The problem of an application failing to run correctly arise due to differences in configuration underling library requirements and other dependencies.     Containers address this problem by providing a lightweight, immutable infrastructure for application packaging and deplyment.

  example:
  -------
  
  ### Before Containers:
  App1, Configurations, Dependancies
  
  ### After Containers:
  Configurations, Scripts, App1, Dependancies
  
  # What is Docker ?
  * Docker is an open source platform for building, deploying, and managing containerized applications.
  * Docker is a software platform that allows you to build, test, and deploy applications quickly.
  * Docker packages software into standardized units called containers that have everything the software needs to run including libraries, system tools,       code and runtime.
  * Docker containers can run anywhere, on-premises in the customer datacenter, in an external service provider or in the cloud.
  * 

  ## Components of Docker ?
  #### The Core of the Docker consists of
  ###### - Docker Engine
  ###### - Docker Conatiner
  ###### - Docker images
  ###### - Docker CLI
  ###### - Docker daemon
  
  * The Docker engine is a part of Docker which create and run the Docker containers.
  * The Docker container is a live running instance of a docker image.
  * The Docker daemon process is used to control and manage the containers.

   ###### Docker Server:
   Pulling images, managing conatiners (Container Runtime, Volumes, Networks, Images)

   ###### Docker API: 
   Interacting with docker components

   ###### Docker CLI:
   Command line interface for executing docker commands.
   ----------
