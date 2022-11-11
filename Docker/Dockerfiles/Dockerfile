#FROM defines the bases image
FROM ubuntu:latest 
### USER is use to define the user that will execute or run RUN, CMD, ENTRYPOINT
USER root
#RUN is use to manage software packages dependencies and library  
RUN apt-get update -y
RUN apt-get install apache2 -y
### LABELS are use to define app metadata
LABEL app-name="webapp"
LABEL environment="dev"
ENV project-name ssc-svcd
## ENTRYPOINT is use to start the app at run time 
## You can either use ENTRYPOINT or CMD
ENTRYPOINT [ "apachectl -D FORCEGROUND" ]
