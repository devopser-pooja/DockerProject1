# DockerProject1
RDS-MariaDB

Steps of Project:
1.Create RDS with Mariadb engine
2.Launch Instance
3.Install Docker Engine
4.Install DB Engine - Mariadb 
5.Clone the Repository which was created by Devloper Team
6.Enter in Project and connect to a MySQL database hosted on Amazon RDS 
     -Create database springbackend
     -Gives the admin user full access (all privileges) to the springbackend database. 
7.Afterthat import a sqlfile(springbackend.sql)into a MySQL database hosted on Amazon RDS
8.Come to Backend Directory and create dockerfile 
9.Create docker image, run the container and go to the src/main/resources and open application.properties and add database endpoint and user/pass.
10.Afterthat come to angular-frontend directory and create dockerfile and then create docker image, run the container. After this process go to the src/app/services directory and open worker.service.ts file. Edit in that file with Ip address and port.
11.Go to the browser and ip address with 8080 port, white error page will be display on your screen. After that enter ip with 80 port, you will see the application working smoothly.
