# CS_437_Lab_2_Final

This repository holds the final version of the lab 2 code written by Emma Chen, William Yeh, Surag Nuthulapaty, and Michael Karpov.

It was copied over from our development github, which will soon by updated with lab 3, lab 4, and lab 5 code since we will likely use a similar codebase for the car in those.

The base tempalte we used for a lot of the code in this lab was given by the started code. This is why the code tree looks the way it does, especially for the frontend.

The format of this repository is as follows:

```
📦 .
├─ Code
│  └─ Server
└─ iot-labs
   └─ iot-labs-2
      └─ frontend-tutorial
```

## Raspberry Pi Server
To run the server, execute the following commands on the raspberry pi: 

```
cd Code
sudo python setup.py
cd Server
sudo python wifi_server.py
```

## Browser Frontend
To run the frontend, execute the following commands on your laptop:

```
cd iot-labs/iot-labs-2/frontend-tutorial
npm i
npm start
```

