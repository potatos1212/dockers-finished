# Docker-compose README.md

The program prints the string "He Who Must Not Be Named" -

In order to run this docker you will need to have the files inside of a directory of your choosing together and not inserted into other directories.

TREE EXMAPLE  
|  
    | Dockerfile  
    | docker-compose.yml  

The commands needed in order to run the specified dockerfile are the following:

Note, you need to run them as sudo. You may need to type in the command of "sudo su" or add "sudo ;command;" before each of the upcoming commands: 

- docker-compose up --build
- docker-compose run app