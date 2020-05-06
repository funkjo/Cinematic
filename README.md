# Cinematic  
  
A movie rental system created as a school project for CSC 445 Software Engineering.  
This project is powered by python and the Flask framework.  
  
Contributors:  
**John Funk**  
**Jon Linton**  
**Wes Thompson**  
**Jesvian Villarroel**  
  
## Installation guide  

Download this project by clicking the big green button in the top right, then clicking Download ZIP. Then unzip the file.

If you do not have python 3 installed on your machine, click the following link and follow the instructions to download python for your operating system:
[Download Python](https://realpython.com/installing-python/)

After this project has been downloaded, navigate to the downloads folder in your terminal or console.  
Ex:
`cd Downloads`

Then, navigate into the project directory:
`cd Cinematic-master`  
  
Next, create a virtual environment in that directory: 
**On Mac** 
`python3 -m venv venv`  

**On Windows**
`virtualenv venv`
  
Activate your virtual environment.  
**On a Mac**  
`source venv/bin/activate`  
  
**On Windows**  
`venv\Scripts\activate`  

Next, download all of the project dependencies:  
`pip install -r requirements.txt`  
  
Finally, run the application:  
**On a Mac**  
`python3 movie-rental-system.py`  

**On Windows**  
`movie-rental-system.py`
  
In your favorite browser, navigate to this URL:  
`http://127.0.0.1:3001/`

To stop the application press `ctrl + C`