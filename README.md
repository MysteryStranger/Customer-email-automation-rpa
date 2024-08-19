Customer-email-automation-rpa
Hello there and welcome to my little bot project here i can show you how we can create a little project so lets start!
First we need a Ui path Studio Download this from official site
![Screenshot 2024-08-17 184946](https://github.com/user-attachments/assets/a98b29e2-c902-45fd-b60b-117ed0cce217)

There you go! now we need to open our project to open project: click the open and choice file (.json)

![Screenshot 2024-08-17 184704](https://github.com/user-attachments/assets/da25b8d7-0bf1-4f55-8a7d-a67d10c2600e)
![Screenshot 2024-08-17 184739](https://github.com/user-attachments/assets/78e7ffe4-d9b7-4427-b6fe-44bd98556629)

There we go now we are starting 

![Screenshot 2024-08-17 184637](https://github.com/user-attachments/assets/e11d26ea-487f-496a-97b9-aeb1e8c36428)

here we get some window so just click on open main 

![Screenshot 2024-08-17 184816](https://github.com/user-attachments/assets/6a79fc3e-4f26-401a-95a5-54eb700832b6)

So we need to create excel file with some data

![excel](https://github.com/user-attachments/assets/a102b662-c5fa-405c-a1a8-f0ed602b8084)

Then we have a pic of our project take a look
![1](https://github.com/user-attachments/assets/0e8d3fd0-725c-43d7-9daa-aa65468f629f)

first step is Use excel file we peek correct excel file with our data
![2](https://github.com/user-attachments/assets/23a7d2eb-b657-4b00-bda3-59be51d21c96)


then we need to do read range for (all sheet1) start from a1
![3](https://github.com/user-attachments/assets/184c7cb4-e68b-4793-bee9-bfd9165679b4)

then we need to For each row in data table
we build var dtCustomers and pick this
![4](https://github.com/user-attachments/assets/da84d3ce-8b22-45b5-812e-e73b7ff1d072)

in body we create variables name,email,category,from price....
here you have two picks of values and process
![5](https://github.com/user-attachments/assets/d9135432-59fc-4fdf-8f05-4d938a207aa2)
![value](https://github.com/user-attachments/assets/ba7e5a9a-269b-4013-b3d5-f5ed94e9f3e3)

here we open our adress we need to get Extensions for our browser
![6](https://github.com/user-attachments/assets/d4e838b2-88ba-4d96-a5d4-3177f8ec2c5a)

here we do a little magick like pick with ocr our objeckts from site 
we need to pick things like category,max pice, min price, and get the filter 
of cource we need to pick the formath of screen to take this for html email for persons
![Screenshot 2024-08-20 001350](https://github.com/user-attachments/assets/583e6f7e-b095-45cc-9658-0e74162efeff)

our last step is save the email body assign
and sending SMTP Mail Message
To mail of customers / Subject category 
![7](https://github.com/user-attachments/assets/4223dd69-38b7-4618-8f1c-0159bf23a57f)

Hope you enjoy! in this project you have a presentation and some picks of process 

enjoy ;)






