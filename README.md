# TTA
Team AMJ Sprint 1
Start sprint 1: February 9, 2024
End sprint 1: February 16,2024
Project Deadline: March 22,2023 

For week one: 
Establish the goal of the project:  Translate jarvis in to spanish 
what features we can add to contribute to repo flow as well as find bugs in projects or we can enhance on code in the project.  
Get the code up and running – Compile the get hub code and see what errors show up. 
Project Idea log 
Translation teach it to speak spanish through a.i 
Simplifying Jarvis for everybody
Making Jarvis more personal 
Adding more features like music as well as changing ai voice 
create an installer so you dont have to upload to powershell
Prompt users as jarvis 

					
Goal of week sprint one:  Run and compile the program. 
How we are going to achieve our goal
Create a team’s group chat.
 sending the GitHub link to Jarvis repository 
Download python


week 2
installed Python and IDE

week 3  Andres: Before the sprint 
Failed installing jarvis from sukeesh: https://github.com/sukeesh/Jarvis/tree/master
I was following the github steps to getting started with installation but I keep getting this error for step 2. I already tried their solution 1. Did any of you manage to install it?, if so can you share your steps as well as your environment variable system PATH. I'm not sure if I made a mistake installing python.
 

I tried looking into the Jarvis/Installer folder and checked unix_windows.py and helper.py. It seems there is a problem with the names of IS_WIN, log_init, and log_close. I believe from unix_windows.py it should be IS_WIN but right now it's is_windows. Also, in helper.py, I found the same issue where init_log should probably be log_init. I'm not sure if I'm the only one with this problem, as I was looking at the deployments in github and there seem to be frequent pull requests about installation. I think we can work on fixing this problem. Let me know what you think about this.
 Join gitter chat https://app.gitter.im/#/room/#Sukeesh_Jarvis_Lobby:gitter.im
Google API Translation https://codelabs.developers.google.com/codelabs/cloud-translation-python3#0

Week three Alyaa:  Before the sprint 
Successfully installed jarvis from sukeesh: https://github.com/sukeesh/Jarvis/tree/master

Python Releases for Windows | Python.org
Week Three Jo : Before the sprint 
Jarvis two github link: https://github.com/projectswithdigambar/jarvis/
I  found the back up plan.  If we could not add to the bigger open source jarvis.  I found a youtuber who has his own channel with videos that help you set up your jarvis and join his open source.  The smaller the open source community of jarvis. The better the chances will be to add our translator project to his open source. I am using studio code and html to connect jarvis online. I have animated how my Jarvis will look however I have not finished putting in coding user responses. Installed github.

 week 3  sprint Objective : 2/23 -3/1
Decide to which jarvis we should use -
     Contact the backup plan open source community -
    verify that jarvis one does not have a spanish translator -
Schedule a zoom meeting
upload the google doc to github
Jo Week Goal : Set up jarvis two github open source - and finish fixing shadow  animation for  the jarvis bot and input a user input text box 
Contact jarvis two creator about any bug as well as look up a translator open source  

Andre week three Goal: Contact supkesh the Jarvis one creator to clarify the installation process and report bugs that I found. Find a translator open source 
Alya:

Week four Andres: Before Friday meeting
Follow up to our back up plan and installed jarvis from digamabar repository. Installed all the required libraries and find out he doesnt have any instructions to do this. Therefore, we can work on a read.me to make it easier to installe for other people. In addition to this, I work on a small program to test the googletranslator librarie. It was a success, so I start working on our feature. Managed to completed it but unfortunatly I cant tested it as right now theres seem to be an error on my engine folder. 

Week five Goals: Install all librarys and create are readme file with the installation instructions For Both . 
Goal  Number two - Have the jarvis running online.
Goal Number three fixing the egine code 




























Read Me RUFF Draft 
EAD ME :ruff draft

Startup with ProjectsWithDigambar What you need to download in part one:

Python: Python is essential for developing the backend of the Jarvis project. It's required to have Python installed on the system to run the Python code.
HTML, JavaScript, Bootstrap: These are the languages and frameworks used for frontend development. While HTML and JavaScript are standard web development languages, Bootstrap is a popular CSS framework for building responsive and visually appealing web pages.
Live Server Extension: The transcript mentions using a live server extension to preview HTML files. Although the specific extension is not mentioned, one popular option is the "Live Server" extension available for various browsers.
Particle.js: Particle.js is a JavaScript library used for creating interactive particle animations on websites. It seems that Particle.js was downloaded or referenced for integrating particle animations into the Jarvis project.
Textillate.js: Textillate.js is a JavaScript library for creating text animations on web pages. It appears that Textillate.js was used for animating text elements in the Jarvis project.
Git: Git is a version control system used for tracking changes in project files and collaborating with others. The transcript suggests setting up a Git repository for the Jarvis project, indicating the use of Git.
GitHub: GitHub is a platform for hosting Git repositories. The transcript mentions creating a repository on GitHub for storing the Jarvis project files and collaborating with others. It implies that GitHub was used as the hosting platform for the project repository.
  Setting up youu jarvis with ProjectsWithDigambar Project Video 2

Pip install git

Virtual Environment: create the environment. python -m venv <virtual_environment_name> pip install git use the Python's built-in venv module or possibly third-party tools like virtualenv or conda to create isolated Python environments for the project.

HTML and JavaScript: HTML and JavaScript are used for designing the frontend of the Jarvis project. script src="/path/to/your/script.js"></script>

Browser: The default web browser on the system (likely Google Chrome) is mentioned in the context of opening the frontend in "up" mode.

: import os os.system("start chrome --app=") These are the programs or components that are explicitly mentioned or implied to be used in completing the Jarvis project according to the provided transcript. Other tools or libraries might also be used depending on the specific requirements and functionalities of the project.

  Setting up youu jarvis with ProjectsWithDigambar video 3 part 3

Obtain the CDN link for the Siri Wave JavaScript library. JavaScript library for creating Siri-like wave animations. It appears that you'll need to include a CDN link to this library in your HTML code. Add the CDN link to your HTML file, preferably at the end of the body section.
Part Two: • Open a terminal or command prompt. • Install Python if you haven't already. • Use pip to install the required libraries, specifically playsound version 1.2.2:

• pip install pip install playsound==1.2.2

Setting up youu jarvis with ProjectsWithDigambar Part 5 video 5

Install pyttsx3 library: The first step is to install the pyttsx3 library, which is used for text-to-speech conversion. You can install it using pip, a Python package manager. bashCopy code pip install pyttsx3
Verify installation: After installing pyttsx3, verify that it has been installed correctly. You can do this by checking the installed version or by importing it in a Python script and ensuring there are no errors. pythonCopy code import pyttsx3
Set up a virtual environment (optional): It's recommended to work within a virtual environment to avoid conflicts with other Python projects. If you're not familiar with virtual environments, you can set one up using virtualenv or venv. bashCopy code
Using virtualenv
source venv/bin/activate

Using venv (Python 3.3+)
python3 -m venv venv source venv/bin/activate. 4. Test text-to-speech conversion: Once pyttsx3 is installed, you can test it by writing a simple Python script to convert text into speech. pythonCopy code import pyttsx3 def speak(text): engine = pyttsx3.init() engine.say(text) engine.runAndWait() if name == "main": speak("Hello, I am Jarvis, your virtual assistant.")

Run the script, and you should hear the text being spoken aloud. 5. Configure voice settings (optional): You can customize voice settings such as voice type and speech rate using pyttsx3's properties. Refer to the pyttsx3 documentation for more information on available properties and how to use them. 6. Further development: With the basic setup complete, you can continue developing your Jarvis Voice Assistant by adding more functionality, such as voice recognition, natural language processing, and integration with other APIs and services. By following these steps, you should be able to set up a Python environment for converting text into speech and start building your own voice assistant similar to Jarvis. what programs were downloaded to complete this project

Setting up youu jarvis with ProjectsWithDigambar Video6

SpeechRecognition Library: This library provides easy access to various speech recognition APIs, allowing Python programs to recognize speech from audio input.
PyAudio Library: PyAudio is used for audio input and output. It provides Python bindings for PortAudio, which is a cross-platform audio I/O library. These two libraries were downloaded using the pip package manager, which is the standard tool for installing Python packages. The specific commands used to install these libraries were: bashCopy code pip install SpeechRecognition pip install PyAudio These installations enabled the Python script to utilize speech recognition functionality and interact with audio input/output devices, ultimately facilitating the creation of the Jarvis voice assistant.
  Setting up youu jarvis with ProjectsWithDigambar online video 7

Set Up Environment: • Make sure you have Python installed on your system. You can download and install it from the official Python website.
Code Base: • Create a project directory for your Jarvis project. • Set up the backend (Python) and frontend (JavaScript, HTML, CSS) files within this directory.
Install Dependencies: • Install any required Python packages using pip. Based on the transcript, it seems like there might be dependencies like speech_recognition, pyttsx3, etc. • Ensure you have any necessary frontend dependencies like jQuery or other libraries.
Write Backend Code: • Follow the instructions in the transcript to write Python functions for voice recognition and processing. Ensure you expose necessary functions using @expose.
Write Frontend Code: • Create a JavaScript file (controller.js as mentioned in the transcript) for frontend functionality. • Link the JavaScript file in your HTML file using <script src="controller.js"></script>.
Communicate Between Backend and Frontend: • Implement communication between backend (Python) and frontend (JavaScript) using functions. Make sure to call Python functions from JavaScript and vice versa as required.
Display Text on Frontend: • Update the HTML and CSS files to display text or messages from the backend (Jarvis) on the frontend.
Test Your Assistant: • Run your Python script and open your HTML file in a web browser to test your Jarvis voice assistant. • Ensure that voice recognition, text display, and other functionalities are working as expected.
Handle Events: • Handle events such as clicking the microphone button to trigger voice recognition and processing.
Debugging and Refinement: • Debug any issues encountered during testing. • Refine the user interface and functionality based on feedback and testing results.
Deployment: Once satisfied with the functionality, you can deploy your voice assistant application.
About
r





























   
Canvas Activity version control			
