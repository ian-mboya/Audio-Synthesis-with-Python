# Audio-Synthesis-with-Python
## Awesome way to record and  process audio in Python

![readme thumbnail](https://github.com/ian-mboya/Audio-Synthesis-with-Python/assets/68651784/fa141de4-abde-4e11-801b-dfdcf4796096)



Recording audio and plotting it's attributes graphically is as easy as it comes. In this project, I demonstrate how to use PyAudio, Python's cross platform I/O library that gives you the ability to record and play audio.
Matplot is the tool that turns our audio output into a graphicall representation.



This project was inspired by freecodecamp and Assembly Ai and I thought it would inspire others as well.

## Requirements
* Python version 3.7+
* Numpy
* Pyaudio
* Matplotlib


## Setup

We will need to activate our Python Virtual environment.
If you are using Visual Studio Code, it is simple.
For this to work, you need to have Python extension installed on Visual Studio Code.

![image](https://github.com/ian-mboya/Audio-Synthesis-with-Python/assets/68651784/1a802f27-db2b-4aed-95e1-7bb48d0da516)

The next step is to activate our Virtual Environment which will allows us to install the packages we need for the project.
To activate the virtual environment press ctrl+shift+p to open the command pallete.

![image](https://github.com/ian-mboya/Audio-Synthesis-with-Python/assets/68651784/339b7e36-a8df-46e3-a5af-1d78a7763566)

In the next step, select your environment type.
In our case we will select Venv instead of Conda.

![image](https://github.com/ian-mboya/Audio-Synthesis-with-Python/assets/68651784/a993970e-9c5a-4b98-ad0e-df3afc7d04db)

Next we need to select the Pyhon interpreter.

![image](https://github.com/ian-mboya/Audio-Synthesis-with-Python/assets/68651784/1ca98af3-8236-467a-ba34-4db3b1114f60)

After selecting the desired interpreter or Python version, a notification will show the progress of the environment creation and the environment folder will appear in your workspace.

![image](https://github.com/ian-mboya/Audio-Synthesis-with-Python/assets/68651784/20b9af7c-8540-4c8b-95e8-3656cf722192)

To activate your virtual environment, Head over the primary sidebar on VsCode. Locate the .Venv directory on the Explorer Window.

![image](https://github.com/ian-mboya/Audio-Synthesis-with-Python/assets/68651784/57a3504d-db3f-476f-aa6d-d84de4df9b13)

Next locate the Scripts directory and click on Activate.ps1 powershell script

![image](https://github.com/ian-mboya/Audio-Synthesis-with-Python/assets/68651784/5ffa8a5e-3ea1-4d18-ab7f-6353fffc6ea0)

The powershell script activates python virtual environment.
You should see this on your terminal to notify you that virtual environment has activated.
![image](https://github.com/ian-mboya/Audio-Synthesis-with-Python/assets/68651784/6c885df5-ff65-4bcd-a275-e7e011eaf771)

The green (venv) indicator shows that your environment has been activated and now we can install the necessary libraries.
Run the following commands to install the python libraries for this project.


```
$ pip install pyaudio
$ pip install numpy
$ pip install matplotlib
```
Your installation should be successful and now we can dive into the project.




