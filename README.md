# Android-Client-Server-Process-Management


Report:
https://docs.google.com/document/d/1Dqhsl8mBaC_kw02APLBqE5KbM7Pbk60SYF3gviZf9yM/edit?usp=sharing
Slides:
https://docs.google.com/presentation/d/1MkH9UxxiG5LUE8OsdOIGBPrEd0nfgBUgti8SpDbQoos/edit?usp=sharing

Run the server with the server code in server-C program folder


gcc -o server serverFinal.c to compile


./server 10023 to run the server


any port number within 16bits and not be used.



*******


Run the C client in client-C program folder


gcc -o client client


./client 0.0.0.0 10023


or:


./client localhost 10023


or run client on the other machine with the ip address of server


use hostname -I to check the ip address of the server


137.207.82.51 on charlie


137.207.82.53 on bravo


********


Open existing project of android client project in :


LearnLinux-LinuxRemote folder which is the linux remote command executing system


LearnLinux-Blog folder which is the remote system integrated in the blog system power by Firebase Android


Other details about how to test and use the functionalities of the project both server and client also the development process of the project are accessible in the final report with the google doc link:

