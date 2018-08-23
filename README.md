# spring-boot-docker-example #
Dokerizing the addition service


## How to run ## 
1. Start the docker and command prompt.
2. ```mvn clean install.```
3. ```docker images``` (verify whether the image is in the list or not)
4. ```docker run -p 8080:8080 addition-service```
5. Open another command prompt and ```docker-machine ip``` and get that <ip>.
6. Open the browser and go to ```<ip>:8080/add/2/3```
7. You will get the response back. :-)