# python3HTTPSAuthServer
A HTTPS SERVER WITH USERNAME AND PASSWORD PROTECTION AS WELL FROM PYTHON3
###
#DO THE FOLLOWING

Enter the following into terminal to install the server files on your Macintosh or Linux:

`pip install python3HTTPSAuthServer`

Create a private key and certificate (key.pem and cert.pem) for your private server's SSL encryption by entering the following in terminal:

`openssl req -x509 -newkey rsa:16384 -keyout key.pem -out cert.pem -days 36500`

You will be asked to enter information regarding the entity responsible for the SSL certificate and key including a PEM password for the SSL encryption.

Choose the appropriate active directory in terminal in order to host that file tree and organize your files to be shared on the IP address of your computer (on Macintosh you can find the computer's IP address in System Settings). With this capability you can enter the IP address and port number at another computer in a different location to access the file directory tree as long as you are running the computer and actively hosting the files through terminal. You can share files over the wireless internet connection instead of a manual file sharing technique or bluetooth. 

`python3 -m python3HTTPSAuthServer --ip [IP address] --port [PORT #] --auth 'username:password' --https --cert /PATH/TO/CERT/cert.pem --privatekey /PATH/TO/KEY/key.pem`

This will put the computer online at the specified IP address and port. 




















