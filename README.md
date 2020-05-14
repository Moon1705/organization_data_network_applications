# organization_data_network_applications
This project was created to pass the PZ on the subject "Organization of data in network applications". 

# Description
The project creates a web-server nginx, CGI gunicorn and project on the Python3.

# Work

**Warming! Start Hardware virtualization and see that port 80 and 8000 is free**

Install docker on terminal Linux (Debian):
```sh
$ sudo apt install docker
```

Install docker on powershell Windows 10:
```sh
> cd C:\Users\$env:UserName\Downloads
> Invoke-WebRequest -Uri https://download.docker.com/win/stable/Docker%20Desktop%20Installer.exe -OutFile Docker_Desktop_Installer.exe
> .\Docker_Desktop_Installer.exe
```

Start and stop on the Linux (Debian):
```sh
$ docker-compose up -d
$ docker-compose down
```

Start and stop on the Windows 10:
```sh
> docker-compose up -d
> docker-compose down
```
