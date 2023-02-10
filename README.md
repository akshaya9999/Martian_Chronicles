# 🚀 MARTIAN CHRONICLES

This project provides an easy to use and user friendly application that retrieves images from NASA's Curiosity,Opportunity and Spirit rovers and displays it . The application also provides an option to send the retrieved images via mail.

![Screenshot from 2023-02-10 22-08-49](https://user-images.githubusercontent.com/116485510/218149636-1ce484d6-e3ff-4a8b-9aab-0ae1c6ce1c70.png)



## 👩‍💻 Technology Stack
- Python
- PyQt

## 🛠 Installation instructions 

Write the following code to clone the repository
```bash
git clone https://github.com/akshaya9999/Martian_Chronicles
```

To install all the required packages type the following code
```bash
pip install -r requirements.txt
```

To Start the application, type
```bash
python3 mainwindow.py
```


## 📚 User Instructions 
### 🖼️ Fetch Image
This page will allow the user to fetch the images based on certain parameters.
The parameters are:

![Screenshot from 2023-02-10 22-09-46](https://user-images.githubusercontent.com/116485510/218149760-a794cb00-6bd7-4e06-949f-04abe6b3f07d.png)


#### 1)Rover name
- Curiosity
- Opportunity
- Spirit

#### 2)Rover Cameras
- FHAZ	 : Front Hazard Avoidance Camera
- RHAZ	 : Rear Hazard Avoidance Camera
- MAST	 : Mast Camera
- CHEMCAM  : Chemistry and Camera Complex
- MAHLI	 : Mars Hand Lens Imager
- MARDI    : Mars Descent Imager
- NAVCAM 	 : Navigation Camera
- PANCAM 	 : Panoramic Camera
- MINITES  : Miniature Thermal Emission Spectrometer (Mini-TES)

#### 3)Earth date
- Date on earth

### 📩 Send Mail
This page will allow you to send the images as attachments to the mail.The user will be able to send it to as many people as they want.

![Screenshot from 2023-02-10 22-11-25](https://user-images.githubusercontent.com/116485510/218149828-280655a6-39af-410e-8ac7-d7f221cb994e.png)


### 📋 Extra Features
- The total number of images fetched will be displayed to the user 
- In case the specifications that the user mentioned returns zero images,they will be presented with a prompt asking them to enter new specifications.
- On sending the email, the user will be informed if the process was succesful or not with a pop up box.
- The user also has an option to view the simplified version of the instructions in the main page



## 😊 My Experience
This entire project helped me get familiar with PyQt designer and PyQt in general . My experience from doing 'Automate The Boring Stuff With Python' also helped in implementing the functionalities of the application, especially with the modules shutil, requests, os, ezgmail and pathlib.
I was also able to learn few of the widgets in PyQt5.
Overall this project was a great opportunity for me to learn and I hope that my efforts will be taken into consideration and I will be able to join the club.



