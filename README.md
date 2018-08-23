### Prerequisits : Docker & Docker Compose 

Install Docker & Docker Compose

```
$ sudo wget -qO- https://get.docker.com/ | sh
$ sudo usermod -a -G docker $USERNAME
$ sudo curl -L https://github.com/docker/compose/releases/download/1.21.2/docker-compose-$(uname -s)-$(uname -m) -o /usr/local/bin/docker-compose
$ sudo chmod +x /usr/local/bin/docker-compose
```
### How to use ? 

- Run your project with php5 
    ``` 
    $ docker-compose -f php5.yml up 
    ```

- When you are done using php5 make sure you stop it with 
    ````
    docker-compose -f php5.yml down 
    ````

- Run your project with php7
     ``` 
     $ docker-compose -f php7.yml up 
     ```

- When you are done using php7 make sure you stop it with 
    ````
    docker-compose -f php7.yml down 
    ````


