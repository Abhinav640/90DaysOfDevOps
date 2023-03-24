# Day 3

What is the linux command to

1. To view what's written in a file.

command: cat file_name
![image](https://user-images.githubusercontent.com/99756745/227437819-14f7dcd9-df39-4cc4-90df-d03f47e4100d.png)

2. To change the access permissions of files.

command: chmod 777 file_name

for example below is the screenshot of the file befor using chmod command
![image](https://user-images.githubusercontent.com/99756745/227438228-85493c66-cbf1-428e-b7c1-21dc74b7e651.png)

We'll try changing the access permission for the hello.txt using the command "chmod 777 hello.txt"
![image](https://user-images.githubusercontent.com/99756745/227438636-5fdaec62-8aa2-494c-9e5b-8fa221950fb2.png)

Now you can see executive access has also been given to all class of people.

Here, 777 is a binary that desides which access should be given to which class of people. Below is the screenshot for a quick understanding. 
![image](https://user-images.githubusercontent.com/99756745/227440594-f60d1c85-2921-4941-b5e5-6e3be73edaf6.png)

For example, if we wanted to give the permission to the user only then we would have used command "chmod 766 hello.txt"
![image](https://user-images.githubusercontent.com/99756745/227441151-ddd9d7b4-1d89-41ad-8cbb-8f69a151ac3b.png)


3. To check which commands you have run till now.

command: history

![image](https://user-images.githubusercontent.com/99756745/227441445-847b4784-8ad9-43c2-bd60-ea3c25ed7ad4.png)

4. To remove a directory/ Folder.

command: rm -r file name
![image](https://user-images.githubusercontent.com/99756745/227441659-2d43a5bf-7474-4bd9-b621-95e0277c288b.png)

5. To create a fruits.txt file and to view the content.

command to make a file and add the content: nano fruits.txt or vim fruits.txt
command to see the file content: cat fruits.txt
![image](https://user-images.githubusercontent.com/99756745/227442304-2ea7c6c1-ec87-4fcc-b05d-9572bb867d92.png)

6. Add content in devops.txt (One in each line) - Apple, Mango, Banana, Cherry, Kiwi, Orange, Guava.

command: touch devops.txt | echo -e "Apple\nMango\nBanana\nCherry\nKiwi\nOrange\nGuava" > devops.txt
Here, "touch" is used to create a file without opening the file.
"|" is used to combine multiple commands
"echo" is used to print the fruits and "-e" is used to interprete backslash escapes "\n". Without "-e", "\n" would have been interprated as literal string and was printed
"> devops.txt" is used to add the output of "echo" command to the file "devops.txt"
![image](https://user-images.githubusercontent.com/99756745/227449805-470951fd-7ddc-40e4-a148-dbd75cd0eca1.png)

7. To Show only top three fruits from the file.

command: head -n 3 devops.txt
![image](https://user-images.githubusercontent.com/99756745/227453086-435260d6-ad72-4564-ad26-22144131a0b2.png)

8. To Show only bottom three fruits from the file.

command: tail -n 3 devops.txt
![image](https://user-images.githubusercontent.com/99756745/227453284-9296bb37-5c57-4473-b992-e193b20e0eda.png)

9. To create another file Colors.txt and to view the content.

command to create a file: touch Colors.txt
command to view the content: cat Colors.txt
![image](https://user-images.githubusercontent.com/99756745/227453707-8d0cd66e-1cd6-42f1-b694-65c813525731.png)

nothing is written in the file

10. Add content in Colors.txt (One in each line) - Red, Pink, White, Black, Blue, Orange, Purple, Grey.

command: echo -e "Red\nPink\nWhite\nBlack\nBlue\nOrange\nPurple\nGrey" > Colors.txt
![image](https://user-images.githubusercontent.com/99756745/227454178-9c115ad6-dcea-40f0-b522-26b1b2b85035.png)

11. To find the difference between fruits.txt and Colors.txt file.

command: diff fruits.txt Colors.txt
![image](https://user-images.githubusercontent.com/99756745/227454542-7608fefc-78af-4a08-8197-900a292be5d1.png)
