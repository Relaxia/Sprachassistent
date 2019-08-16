# Sprachassistent

This project was created for the bachelor thesis of Robin Kaufmann

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.
Make sure you follow the following steps.

### Prerequisites

1) 	You need the Python Version 3.6.2. in the 32bit Version.
	Please visit https://www.python.org/downloads/release/python-362/ to download the installer of your operating system
	
2) 	Open the project in your IDE
	
2)	You need to set your project interpreter to this python version in your IDE

3)	Make sure you install the following prerequisites:
	ibm-watson
	pyaudio
	websocket-client
	requests
	
	You can use pip to install these.

```
pip install --upgrade ibm-watson
pip install pyaudio
pip install websocket-client
pip install requests
```

4)	Make sure you have a microphone connected to your device

### Running it

Now you are able to run it. Run with your set interpreter (again, make sure its a python 3.6.2. 32bit interpreter) the frontend2.py

If everything worked fine you should see the following console output

```
Enter CTRL+C or CTRL+F2 if in pycharm to end recording...
Connection was successful
Service is listening
```

Now you are able to speak and see the transcription in the console.

### Example usage

If you want to test the yellow button make sure you said a sentence like:

"Die Adresse ist also der Amselweg" which yields Amselweg as a candidate for the street.
"Ah sie möchten also in Steglitz wohnen" which yields Steglitz as a candidate for the location.
"Das Eigenkapital beträgt also <beliebige Zahl>" which yields <beliebige Zahl> as a candidate for the capital.
"Das Einkommen beträgt also <beliebige Zahl>" which yields <beliebige Zahl> as a candidate for the income.
"Der Kaufpreis beträgt also <beliebige Zahl>" which yields <beliebige Zahl> as a candidate for the price.

### Troubleshooting
If you get an error that the module dateutils is missing, install it using pip
```
pip install python-dateutils
```

If you only get the first line of the console output listed above without error then youre most likley not using the 3.6.2 32 Python Version.

If you do get the above console output but no transcriptions then make sure your microphone is connected and running.

## Authors

* **Robin Kaufmann* - *Initial work* - [Relaxia](https://github.com/Relaxia)


