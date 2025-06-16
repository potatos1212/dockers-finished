# Dockerfile README.md

This README.md will be independent - without the use of docker-compose.

The program will print the string "He Who Must Not Be Named".
You must use the commands while inside of the directory you imported to and with the files not inside other directories, but one next to each other.

TREE EXMAPLE  
|  
    | Dockerfile  
    | docker-compose.yml  

In order to create the image and run it using the Dockerfile, you need to run the upcoming commands as sudo. You may need to type in the command of "sudo su" or add "sudo ;command;" before each of the upcoming commands: 

- docker buildx build -t print_sentence .
- docker run print_sentence