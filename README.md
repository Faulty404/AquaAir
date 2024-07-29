# AquaAir
A webapp which gives the air and water quality index of the location entered by the user.

## Prerequisites:

To run the model on localhost, one must have the django framework installed on the remote device.

Steps to run the server:
1. Enter the working directory for the django folder. In this case it is the src folder.
2. While inside the src folder, open the terminal and type the following command:
 ```Terminal
 $ python .\manage.py runserver
```
3. This command should return a link for the model which is running on a localhost.
4. To get the AQI(Air Quality Index) of a place, click on the AQI button which shall redirect you to a site where you must enter the name of the location you want to inspect the Air Quality of.
5. To get the WQI(Water Quality Index) of a place, click on the WQI button which shall redirect you to a site where you must enter the composition of water to assess its potability.

In case some errors occur due to missing dependencies, please install them on your local device using the pip install command.

### User Interface :
![image](https://github.com/user-attachments/assets/670e92b5-1b90-4903-b7f2-8faab4229665)



### How does it Work ?

![alt text](https://github.com/Faulty404/AquaAir/blob/main/use%20case%20diagram.png)



