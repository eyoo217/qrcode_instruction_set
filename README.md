# qrcode instruction set

### Hi, I will be showing you how to create a qr code generator in Python using the qrcode library.

## Step 1: Open an IDE
### We need to use an IDE that supports python, such as VSCode and IntelliJ.
### For this tutorial I will be using VSCode.
### You can install VSCode here at, https://code.visualstudio.com/

## Step 2: Create a new project!
### Lets open VSCode and you should see an option to open a folder
![Screenshot 2024-10-08 151549](https://github.com/user-attachments/assets/ce3e369e-a041-417f-9084-9d1d397a45c5)
### Select open folder and you will be brought to your User directory.
### Inside your directory create a new folder and name it "qr_code".
![Screenshot 2024-10-08 151635](https://github.com/user-attachments/assets/67cd4bc1-5fcf-47fb-b422-21aa44ad22f4)
### Then select open folder
![Screenshot 2024-10-08 151657](https://github.com/user-attachments/assets/06ab74f2-a9e3-4c60-9639-46a6fcb4e35d)

## Step 3: Setting up our environment
### Now inside VSCode you will have an empty project
### Create a new terminal in the terminal tab on the upper left hand corner.
![Screenshot 2024-10-08 152434](https://github.com/user-attachments/assets/0d740ee4-2513-4f1f-a1b9-528c2b752cf3)
### First we want to check if we have python installed. We can check this by running python -V
![Screenshot 2024-10-08 151753](https://github.com/user-attachments/assets/ad65c653-b75a-4059-9b3d-7d40c94d3de5)
### If correctly installed, we should get the version of python we have currently installed.
### Otherwise if we do not have python installed, we need to navigate to the Microsoft Store and install python.
### You can find this at, https://www.microsoft.com/store/productId/9NRWMJP3717K?ocid=pdpshare

### Once python is installed we want to create a .venv or virtual environment.
### We do this by running python -m venv \PATH\ where \PATH\ is the location to where your project is located
![Screenshot 2024-10-08 153056](https://github.com/user-attachments/assets/15cd1607-32e4-4291-b5a8-54e1e1f23baf)

### Once you run this, you should see 3 directories and a config file appear in your explorer
![Screenshot 2024-10-08 151840](https://github.com/user-attachments/assets/4b9ff1fe-acfe-48d2-85a6-516ca00b8762)

## Step 4: Installing QR Code
### Now that our environment is set up, lets install qrcode.
### To do this we will run pip install qrcode
![Screenshot 2024-10-08 153600](https://github.com/user-attachments/assets/6173de78-20e0-476d-996e-e70326bdb7e6)
### Once thats installed we can now start writing our code.

## Step 5: Create a new file
### Navigate to your explorer and right click, then create new file
### we will name this main.py
