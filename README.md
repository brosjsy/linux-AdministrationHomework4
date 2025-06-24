# linux-AdministrationHomework4
![image](https://github.com/user-attachments/assets/bf533427-1576-4ac6-a204-f944c3dfda0e)

````
#!/bin/bash
echo "hello world"
whoami
hoami
echo
pwd
echo
hostname
echo
ls -ltr
echo
a=joseph
b=Olawoyin
c='oraimo class'

echo "my first name is $a"
echo "my last name is $b"
echo "my computer class name is $c"

echo "What is your first name?"
read a
echo
echo "What is your last name?"
read b
echo
echo Hello $a $b

echo "Hello `whoami`"
echo
echo "Today is `date`"
echo
echo "Number of user login: `who | wc -l `"
echo
echo Enter the file name to be renamed
read oldfilename
echo Enter the new file name
read newfilename
mv $oldfilename $newfilename
echo The file has been renamed as $newfil
````
![image](https://github.com/user-attachments/assets/fa945a75-fc15-43d0-8647-f074d400e340)

![image](https://github.com/user-attachments/assets/861d431f-2c38-46ac-a9b9-b8d2c19cdcb6)

![image](https://github.com/user-attachments/assets/62f6ff65-cfc5-4dac-8052-8134d5d0615a)

![image](https://github.com/user-attachments/assets/cf238191-b6ea-4edc-97ae-4629d3604848)

![image](https://github.com/user-attachments/assets/4bf8ab71-c7d1-4211-9fe7-d626cbc1107f)

![image](https://github.com/user-attachments/assets/3469b0a6-bf0a-4edf-a3dc-0bbd460b11f8)

•	Create a script to the output of ls -ltr to a file called golisting

![image](https://github.com/user-attachments/assets/70a51a49-ecfd-4579-bc69-f1fe81421653)

![image](https://github.com/user-attachments/assets/7fbf06f8-140f-43e1-8891-ec8726603826)

•	Create a script to output "First day of Spring is March 20th"

![image](https://github.com/user-attachments/assets/f1e7560f-2b2a-407c-ad35-bd288ddd76fd)
![image](https://github.com/user-attachments/assets/23c0af46-3999-4915-b93b-23325baee03c)
•	Create a script that will run commands, who, dmidecode, cal, and free

![image](https://github.com/user-attachments/assets/05480630-aaf6-4731-989b-8196fb7128db)

![image](https://github.com/user-attachments/assets/1521b341-b8c3-4eb4-8c58-e9d8e8bafa1d)

•	Create a script that will touch a new file and then change its permissions to read, write and execute for everyone

![image](https://github.com/user-attachments/assets/9ac922b4-6f99-4607-9aee-8a4db764c62f)

![image](https://github.com/user-attachments/assets/e68f83d5-d1e6-43c6-887f-7be4dc158f5c)

•	Create a script that will ask you for your parents name and then output your parents name on the screen as, Your parents names are 

![image](https://github.com/user-attachments/assets/aa9b142c-c5c5-4924-84fd-8b17d30c97b8)
![image](https://github.com/user-attachments/assets/6b823a90-11a7-4ba3-8564-7f8d7fa16147)

•	Create a new file called empty and then write if-then statement to see if it can find any empty files in your home directory.  If yes then it should say "Your file exist"  If it does not then it should say "Your file does not exist"

![image](https://github.com/user-attachments/assets/4034ad06-1548-4d7c-92c2-4941ec812dcf)
![image](https://github.com/user-attachments/assets/fa076497-b38c-44fb-9943-d4df8403cd69)

•	Write a case script that will give the option to the user to run commands as, top, iostat, free, /etc/cpuinfo, dmesg

````#!/bin/bash

# Display menu options
echo "Choose a command to run:"
echo "1) top"
echo "2) iostat"
echo "3) free"
echo "4) /proc/cpuinfo"
echo "5) dmesg"
echo "Enter your choice (1-5):"
read choice

case $choice in
    1)
        echo "Running top (Press 'q' to exit)..."
        top
        ;;
    2)
        echo "Running iostat..."
        iostat
        ;;
    3)
        echo "Running free..."
        free -h
        ;;
    4)
        echo "Displaying /proc/cpuinfo..."
        cat /proc/cpuinfo
        ;;
    5)
        echo "Running dmesg..."
        dmesg | less
        ;;
    *)
        echo "Invalid option. Please choose between 1 and 5."
        ;;
esac
````

![image](https://github.com/user-attachments/assets/6ee5587c-6a23-4841-a870-e109afd24327)
![image](https://github.com/user-attachments/assets/24c28cf0-bb76-4731-895b-a5d664e1c5ed)








