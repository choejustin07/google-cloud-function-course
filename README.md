# Google Cloud Functions Course
## Starting a project 
To start a new project in google cloud we can go to the cloud [Firebase Console](https://console.firebase.google.com) or create it from [Google Cloud Platform Console](https://console.cloud.google.com) 
## Creating a virtual environment
First we have to install `python3-venv` with the following command:
```
sudo pip3 install virtualenvwrapper
``` 
Then we execute the following command:
```
python3 -m venv venv
```
To activate the virtual environment we do: 
```
source venv/bin/activate
```
In order to add new packages to our new virtual environmnet 
we create a file called `requirements.txt` and execute 
the following command:
```
pip3 install -r requirements.txt
```