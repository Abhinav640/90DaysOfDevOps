# day 5

Task 1:
When the script is executed as

./createDirectories.sh day 1 90

then it creates 90 directories as day1 day2 day3 .... day90

Sol:

below is the script:

#!/bin/bash

dir=$1
start=$2
end=$3

for ((i=start; i<=end; i++))
do
        mkdir "${dir}${i}"
done

![image](https://user-images.githubusercontent.com/99756745/227799721-381098cc-ca86-4d40-8c74-501e3040c02e.png)


![image](https://user-images.githubusercontent.com/99756745/227799761-7d69ba2c-9a36-4801-b271-bb6bd95dd6f5.png)


Task 2:
Create a Script to backup all your work done till now.

Below is the script: 


#!/bin/bash

src=/home/ubuntu/scripts
tgt=/home/ubuntu/backups
file_name=$(date | xargs | awk '{print $3"-"$2"-"$6}')

tar -czvf $tgt/$file_name.tar.gz $src

echo "Backup Complete"

![image](https://user-images.githubusercontent.com/99756745/227799875-bdda88ac-82ba-4199-b64b-ba8ee390402a.png)

![image](https://user-images.githubusercontent.com/99756745/227799896-cf80e691-887c-4eeb-88bf-c707bf6ff082.png)


Task 3:
Read About Cron and Crontab, to automate the backup Script

I have made a cron job

![image](https://user-images.githubusercontent.com/99756745/227799978-5527f4e3-39b9-4bbe-bf74-505eab0f8696.png)

This will run every day in morning 8am.


Task 4:
Read about User Management

It is the concept where we can add multiple users to a single system and assign then to a group. Also, we can restrict the permissions for a perticular user or group.


Task 5:
Create 2 users and just display their Usernames

Syntax to add user:

sudo useradd -m abhinav
sudo useradd -m dushyant

![image](https://user-images.githubusercontent.com/99756745/227800340-ecbb253e-f6cd-415f-8fd6-9f51bf71e05d.png)

![image](https://user-images.githubusercontent.com/99756745/227800411-9db5272d-1eda-418a-a5e5-69f444fcf24f.png)
