# docker-ubuntu-trusty64


### How to setup your machine for local development
#### Requirements:

##### Ansible Version 2.0.1.0 or Above.

##### Virtual Box Version 5.0.14 or Above.


1. Run vagrant up:
    ```shell
    $ vagrant up
    ```

2. Run vagrant ssh after the box is up and running:
    ```shell
    vagrant ssh
    ```

3. Check if docker is installed successfully inside of your virtual box:
    ```shell
    $ docker images
    $ docker run hello-world
    ```

4. To restart your docker daemon if you ever need to:
    ```shell
    $ sudo service docker restart
    ```
    :+1:
