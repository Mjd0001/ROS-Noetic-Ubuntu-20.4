# ROS-Noetic-Ubuntu-20.04

## Step1: Ubuntu MATE 20.04 LTS Installation
1- First download the image from here: https://cdimage.ubuntu.com/ubuntu-mate/releases/20.04/release/
2- <br>open VMWare, and select the ‘Create a New Virtual Machine‘ option as shown in the figure below.<br>
![image](https://github.com/Mjd0001/VMWarte-Ubuntu-22.04-installation/assets/105239889/970cf594-3bd1-4e93-b1f0-a5c0ed373442)
<br><br>
3- choose the last option 'I will install the operating system later' : <br>
![image](https://github.com/Mjd0001/VMWarte-Ubuntu-22.04-installation/assets/105239889/9f892bdf-d016-402f-995f-1c785ad234af)
<br><br>
4- Select 'Linux' and 'Ubuntu 64-bit':<br>
![image](https://github.com/Mjd0001/VMWarte-Ubuntu-22.04-installation/assets/105239889/e3fbce6b-c41b-457b-b6de-d0e9457c8684)
<br><br>
5- You can change the Virtual Machine name and the location if you want, or you can keep it as default:<br>
![image](https://github.com/Mjd0001/VMWarte-Ubuntu-22.04-installation/assets/105239889/a7006c86-e8ac-4fe2-b198-7b8414ee43fb)
<br><br>
6-The next step is to assign the size of the virtual hard disk. You can safely work with 20 GB size for hard disk.
There are two options for creating a virtual hard disk. The first option is to store the virtual disk file as a single file. The second option is to split the disk into multiple files. The advantage of splitting is if you want to copy the hard disk file to another computer, you can easily copy the files. The problem with this configuration is, the performance will reduce if the disk size is very high.<br>
![image](https://github.com/Mjd0001/VMWarte-Ubuntu-22.04-installation/assets/105239889/2e245774-1a9a-4a63-8273-5e391b5db51b)
<br><br>

7- Then press the ‘Customize Hardware‘ button<br>
![image](https://github.com/Mjd0001/ROS-Noetic-Ubuntu-20.4/assets/105239889/c39ac96f-ef28-4204-a242-e83fbf5d93d2)
<br>
In memory tab, based on your RAM number you have allocate RAM size, the half is enough.<br>
![image](https://github.com/Mjd0001/ROS-Noetic-Ubuntu-20.4/assets/105239889/68d11864-8bf9-412d-89cd-b1e050b00f08)
<br>
In Processor tab, besed on your CORE number change the number of processor core, 2 is enough for me<br>
![image](https://github.com/Mjd0001/ROS-Noetic-Ubuntu-20.4/assets/105239889/9e0ffd07-ff80-4b25-b30f-54945f15f51c)
<br>
In New CD/DVD (SATA), select 'use ISO image file' and press 'Browse', and go to iso file of ubuntu 20.04 that we download it and choose it:<br>
![image](https://github.com/Mjd0001/ROS-Noetic-Ubuntu-20.4/assets/105239889/d0aa9a82-743f-44c3-ac5c-34406067eeae)
<br>
8- finally click in close button and then Finish button.<br>
you can change these settings when every you want by click on 'Edit virtual machine settings'. and to Run the virtual machine click on 'Play virtual Machine'<br>
![image](https://github.com/Mjd0001/ROS-Noetic-Ubuntu-20.4/assets/105239889/a00eea17-150e-4422-9ee7-6aedac056f58)
<br><br><br>

## Step 3: Ubuntu 22.04 Setup
1- Run the virtual machine by click on 'Play virtual Machine'<br>
2- Select the language 'English' then press 'install ubuntu':<br>
![image](https://github.com/Mjd0001/ROS-Noetic-Ubuntu-20.4/assets/105239889/b7ac7da8-b4a8-4971-9237-dffe61fb10d1)
<br><br>
3- This to change Keyboard Layout ( it is better to not change it , let it stay english as default). then click continue:<br>
![image](https://github.com/Mjd0001/ROS-Noetic-Ubuntu-20.4/assets/105239889/409fca66-be7c-49e8-8af8-b8daaaa56764)
<br><br>
4- In the next window keep every things as default and press continue:<br>
![image](https://github.com/Mjd0001/ROS-Noetic-Ubuntu-20.4/assets/105239889/889139cb-ca50-4d02-976a-b982eaac9c00)
<br><br>
5- Then in the next window, select 'Erase disk and install Ubuntu' (don't be afraid nothing will Erased):<br>
![image](https://github.com/Mjd0001/ROS-Noetic-Ubuntu-20.4/assets/105239889/ffec5386-7f61-4d66-9d07-73b06b3f806f)
<br>Then click 'inatall Now'.<br><br>

6- Then clich continue and choose your timezone:<br>
![image](https://github.com/Mjd0001/ROS-Noetic-Ubuntu-20.4/assets/105239889/5e4f28f1-ea71-4dbc-9f10-46d29d557168)
<br><br>
7- Then Enter your Information (You have to remember the password, it is important), then press continue and it will start installing (it will take a time):<br>
![image](https://github.com/Mjd0001/VMWarte-Ubuntu-22.04-installation/assets/105239889/0dacb3c7-97dc-4169-a194-be4fc40abbd4)
<br><br>
8- Then after installing, press 'Restart Now':<br>
![image](https://github.com/Mjd0001/VMWarte-Ubuntu-22.04-installation/assets/105239889/cc652add-15fd-48e9-b8e9-7b51efd9441a)
<br><br>
9- if you see this screen press Enter:<br>
![image](https://github.com/Mjd0001/VMWarte-Ubuntu-22.04-installation/assets/105239889/77783ebd-088f-470f-874d-33e61bac7014)
<br><br><br>
## Step3: ROS Noetic Installation
follow the instractions here (copy and paste), and make sure to choose Desktop Install: <br>
https://wiki.ros.org/noetic/Installation/Ubuntu
<br><br>
__That's it!__
<br>
