# dyInvoice

Dy-Invoice is an invoicing platform for young entrepreneurs to help them facilitate their customer and invoice management.


Database Architecture

![Capture d’écran 2023-04-21 à 12 29 09](https://user-images.githubusercontent.com/20758818/233614139-a6074f51-2d6a-42c5-b03a-0eb1b31c06a6.png)

PS: There is a relation between Role and User(Many-to-Many). The software that I use don't provide the May-to-Many relationship

## How to install the project

In the DockerFile there are two scripts: Production DockerFile Script and Local Working DockerFile scripts
To work in local you should comment the Production DockerFile Script

![Capture d’écran 2023-04-21 à 12 42 45](https://user-images.githubusercontent.com/20758818/233616696-91f3c32b-79f9-4a0c-93d7-90360fa99662.png)


To start the project

```sh
$ sh start.sh
```

This command will automaticaly launch the project throught the docker-compose.yml
