# ESDE-2022-Ghidra
Ghidra is one of many open source software (OSS) projects developed within the National Security Agency.

#For everbody
Setup:
Go to https://github.com/NationalSecurityAgency/ghidra/releases and download the latest Ghidra 10.2.2 (zip) 

To install Ghidra, simply extract the Ghidra distribution file to the desired filesystem destination using any unzip program (built-in OS utilities, 7-Zip, WinZip, WinRAR, etc)

#Windows:
If not installed already (JDK needs to be 11 or higher) 
Go to https://adoptium.net/temurin/releases/

Extract the JDK distribution (.zip file) to your desired location and add the JDK's bin directory to your PATH:

Extract the JDK:

Right-click on the zip file and click Extract All...
Click Extract
Open Environment Variables window:

Right-click on Windows start button, and click System
Click Advanced system settings
Click Environment variables...

Add the JDK bin directory to the PATH variable:

Under System variables, highlight Path and click Edit...
At the end of the the Variable value field, add a semicolon followed by <path of extracted JDK dir>\bin
Click OK
Restart any open Command Prompt windows for changes to take effect

#Linux and macOS (OS X):
If not installed already (JDK needs to be 11 or higher)
Go to https://adoptium.net/temurin/releases/ 
Extract the JDK distribution (.tar.gz file) to your desired location, and add the JDK's bin directory to your PATH:

Extract the JDK:
tar xvf <JDK distribution .tar.gz>
Open ~/.bashrc with an editor of your choice. For example:
vi ~/.bashrc
At the very end of the file, add the JDK bin directory to the PATH variable:
export PATH=<path of extracted JDK dir>/bin:$PATH
Save file
Restart any open terminal windows for changes to take effect

