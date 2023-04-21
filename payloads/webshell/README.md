# Ironcat Webshell Payload Instructions

## Description
This is a simple webshell, written in golang, and compiled using obfuscation techniques.


In the webshells folder. Host a server so that the webshell.exe file is available.

python3 -m http.server

Now browse to this device at 172.31.24.10:8000

Click the link for the webshell.exe file.

After download, open cmd.exe and browse to the download folder.

cd c:\Users\Public-pswin1\Downlaods

Execute the payload with two arguments.. They can be anything.

ex.  webshell.exe 1 1

Now use your sandbox tooling to detect the activity.

You can browse to localhost:8080 to see your webshell.
