# django-todo
A simple todo app built with django

![todo App](https://raw.githubusercontent.com/shreys7/django-todo/develop/staticfiles/todoApp.png)
### Setup

Create a EC2 instance of ubuntu of instance type of t2.micro in AWS

Edit inbound rules:
    Add Security Rules:
      Create a Custom TCP of Port Range 8000 with source of Anywhere IPv4.

Now Connect the instance.
Update the instance
```bash
  sudo apt update
```

To get this repository, run the following command inside your git enabled terminal
```bash
 git clone https://github.com/0mchoudhary/Django_todo_Docker-compose.git
```

Change the permission of directory
```bash
chmod 777 Django_todo_Docker-compose
```

Install Docker
```bash
  sudo apt install docker.io -y
```
Install Docker Compose
```bash
  sudo apt install docker-compose -y
```

Change the directory
```bash
  cd Django_todo_Docker-compose
```

To Start 
```bash
  sudo docker-compose up -d --force-recreate --no-deps --build web
```

To Stop
```bash
  sudo docker-compose down
```
  

Once the server is hosted, head over to http:$(YOUR_IP_ADDRESS)/todos for the App.

Cheers and Happy Coding :)
