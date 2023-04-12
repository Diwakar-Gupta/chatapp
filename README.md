# ChatApp - Peer-to-Peer Video and Audio Chat Application
ChatApp is a simple poc video and audio chat application that allows users to connect with each other in real-time, without the need for any third-party servers. This is achieved through the use of WebRTC and websockets technologies.

## Features
- Peer-to-peer video and audio chat
- Secure and private communication
- Text chat feature
- Technology Stack
- WebRTC: for peer-to-peer video and audio communication
- Websockets: for real-time text chat and signaling between peers
- Django: for the backend, but don't require this heavy backend


## Installation
To install and run the application, please ensure that you have the following requirements installed on your system:

Python 3
Then, clone this repository and navigate to the project directory:
```shell
https://github.com/Diwakar-Gupta/chatapp.git
cd chatapp
```

Create a virtual environment and install the necessary dependencies:

```shell
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

Now, you can start the server by running the following command:
```shell
python manage.py runserver
```

The application should now be running on http://localhost:8000/.

## Usage
To use the application, simply open a web browser and navigate to the URL where the application is hosted. To start peer call follow steps
1. You will be given a name `Name: yYyVcGEeeqRE`, 
2. copy the id `yYyVcGEeeqRE` and paste it to the other end
3. press the call button on other end
4. you will get connected `Name: yYyVcGEeeqRE` will be changed to `Connected to: yYyVcGEeeqRE`
5. to send video or audio feed tick on the check box. 

## Acknowledgments
This application is created as a proof of concept of WebRTC.This is a simple and secure way to connect with friends and family in real-time. The use of WebRTC and websockets technologies allows for efficient and private communication without the need for any centralized servers.
