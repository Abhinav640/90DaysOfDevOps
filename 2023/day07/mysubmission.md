Task 1.1:
You have to install docker and jenkins in your system from your terminal using package managers

Installing Docker

![image](https://user-images.githubusercontent.com/99756745/229985443-a7ceb22b-4abe-48d0-9f23-5ff114c98180.png)

Installing Jenkins

![image](https://user-images.githubusercontent.com/99756745/230057857-6494366a-f4ce-4c6d-a841-abbe1d1ef2e6.png)

Task 1.2:
Write a small blog or article to install these tools using package managers on Ubuntu and CentOS

Have written but not published


Task 2.1:
check the status of docker service in your system

It is actice and running

![image](https://user-images.githubusercontent.com/99756745/230062893-7a60606d-186f-40d6-92ca-70478543e0c2.png)

Task2.2
stop the service jenkins and post before and after screenshots

Before:

![image](https://user-images.githubusercontent.com/99756745/230063249-829df2bc-de1f-431b-b6af-65b731a8a318.png)

After:

Command: sudo systemctl stop jenkins

![image](https://user-images.githubusercontent.com/99756745/230063602-355a786e-8dbd-4820-a2f2-c9d2a2c9e3a9.png)

Task 2.3:
read about the commands systemctl vs service

Both systemctl and service are commands that can be used to manage services on a Linux system, but they work differently and have different capabilities.

service is an older command that is used to start, stop, restart, and query the status of system services. It is part of the SysV init system, which is used by some older Linux distributions. The command takes a service name and an action to perform on that service. For example, service docker status would show the status of the Docker service.

systemctl is a newer command that is used to manage services in newer Linux distributions that use the systemd init system. It provides a wider range of capabilities than service, including the ability to enable or disable services to start at boot, and to view the logs of a service. The command also takes a service name and an action to perform on that service. For example, systemctl status docker would show the status of the Docker service.

In summary, service is an older command that works with the SysV init system, while systemctl is a newer command that works with the systemd init system and provides more advanced functionality.


