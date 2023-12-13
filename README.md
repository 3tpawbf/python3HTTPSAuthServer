NOT FOR PRODUCTION/PROFESSIONAL IMPLEMENTATIONS. THIS USES A DEPRECATED ALGORITHM OF ENCRYPTION (SSL). FOR MORE INFORMATION ON THE OPTIONS FOR SECURITY SENSITIVE APPLICATIONS, SEE HERE: https://docs.python.org/3/library/ssl.html#

# python3HTTPSAuthServer
A PYTHON3, HTTPS ENCRYPTED SERVER WITH ADDITIONAL SECURITY VIA A USERNAME AND PASSWORD OF UP TO 256 CHARACTERS FOR EACH.
###
#DO THE FOLLOWING

Enter the following into terminal to install the server files on your Macintosh or Linux:

`pip install python3HTTPSAuthServer`

Create a private key and certificate (key.pem and cert.pem) for your private server's SSL encryption by entering the following in terminal:

`openssl req -x509 -newkey rsa:16384 -keyout key.pem -out cert.pem -days 36500`

You will be asked to enter information regarding the entity responsible for the SSL certificate and key including a PEM password for the SSL encryption.

Choose the appropriate active directory in terminal in order to host that file tree and organize your files to be shared on the IP address of your computer (on Macintosh you can find the computer's IP address in System Settings). With this capability you can enter the IP address and port number at another computer in a different location to access the file directory tree as long as you are running the computer and actively hosting the files through terminal. You can share files over the wireless internet connection instead of a file sharing technique that will cost extra overhead like a usb stick or bluetooth. 

`python3 -m python3HTTPSAuthServer --ip [IP address] --port [PORT #] --auth 'username:password' --https --cert /PATH/TO/CERT/cert.pem --privatekey /PATH/TO/KEY/key.pem`

This will put the computer online and accessible to others at the specified IP address and port. I haven't followed up with the current cutting edge in excryption (TSL, ciphers, etc.) of data transfer but this is the most streamlined approach to create a file sharing instance. It uses a self signed SSL certificate so you won't be recognized by anyone else on the internet unless you pay a tax for certificate from a certificate authority. It takes about 1 hour to get your system set up once you have practiced a couple dozen times with Linux, Windows, and MacOS from fresh installs and gotten your file system set up the way you prefer. My current set up is a Linux/Windows tower with a terabyte of storage and a MacOS with a 250 gigabyte laptop for tinkering with the triple boot system. I have about 500 gigabytes of data with about 1.25 terabytes of storage.

With this deployment you can "cloud-host" your files without the cost of utilizing private industry servers to store the data. With this method of home office design you can invest in your own hardware (large data storage hard drives, high quality GPUs, and multiple monitors) to develop your own terms of work within the technological industry. Instead of working for a firm that hordes resources and profits while dumping excess labor and cost on the workers and public sector, you can develop a lower cost, subsistence model with respect to computing and how much of your life should be dedicated to labor with a computer. With this technique you can access any file from anywhere on the planet with an internet connection and a local hard drive to temporarily hold the data. I will continue researching this thread to see how much the hosting directory can be modified for technological ergonomics but with the way the system runs currently, it would be pretty clumsy to try and listen to my Tool discography while visiting Taiwan. It's more for the documentation I have to be accessible anywhere, anytime, with any hardware.






















