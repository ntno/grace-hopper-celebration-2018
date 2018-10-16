# CE503: Docker 101

**What** overview of benefits of using docker containers with hands on component   
**Where** GRB 372C  
**When** Wednesday, September 26, 2018 11:30 AM  
**Who** TACC - Texas Advanced Computing Center  


### goals
* isolate applications
* fix the 'it works on my machine why doesn't it work on yours' problem


#### Docker System
* Docker Container 
  * application 
  * dependencies (bins/libs)
* Docker Engine
  * runs on top of the Host OS 
  
  
#### Docker benefits
* no overhead of having a Guest OS for each application (as is with VMs)
* easy to install/run an application
  * no need to figure out installing correct dependencies because they are included in the container


#### demo
* runx the unix 'date' command 
  * `docker container run alpine date`  
* you can also spin up a container with an interactive linux shell, then exit the container, then come back to the container by "attaching"


### see also
kubernetes - helps you to manage running your containers
vetti - javascript emulator of linux terminal
alpine linux - very lightweight distrubution
agave - TACC system for managing job queues/messages
jetstream - cloud based super computer
