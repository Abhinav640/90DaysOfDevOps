# Day 4

1. Explain in your own words and examples, what is Shell Scripting for DevOps.

Shell scripting is basically a set of command that we write in a file to interact with a Kernel.This eventually help us in automation. 
For example: if we want that once any new instance is created then feature a, feature b and feature c should be enabled by runnung a single command which ideally takes 20-30 commands. Then this can be done using shell scripting.

2. What is #!/bin/bash? can we write #!/bin/sh as well?

This is called the shebang line, this is user to specify the interpreter to be used to execute your shell script.

3. Write a Shell Script which prints I will complete #90DaysOofDevOps challenge

below is the script:

#!/bin/bash
echo "I will complete #90DaysOofDevOps challenge"

![image](https://user-images.githubusercontent.com/99756745/227492441-1495543c-b042-4fb9-b8f9-89b420167af9.png)

![image](https://user-images.githubusercontent.com/99756745/227492572-85eaa4ac-1207-48ad-a670-1e63cfff63e8.png)

4. Write a Shell Script to take user input, input from arguments and print the variables.

below is the script:

#!/bin/bash

echo "enter your input"

read input

echo "this is the user input: ${input}"

echo "this is the argument passed: $1"

![image](https://user-images.githubusercontent.com/99756745/227498335-7651c70a-efcb-4bf0-80b3-6bd747a08cd0.png)

![image](https://user-images.githubusercontent.com/99756745/227498213-265aa088-c358-424f-8d36-954ef58de443.png)

5. Write an Example of If else in Shell Scripting by comparing 2 numbers

below is the script:

#!/bin/bash

number=5

echo "enter a number"

read num

if (( "$num" < "$number" ))
then
        echo "${num} is smaller than ${number}"
else
        echo "${num} is greater than or equal to ${number}"
fi

![image](https://user-images.githubusercontent.com/99756745/227502275-bed58c12-9f40-4917-8cc9-97b27c6a74ae.png)

![image](https://user-images.githubusercontent.com/99756745/227502162-4626b214-aae6-4d19-a368-0f14ccce77b7.png)
