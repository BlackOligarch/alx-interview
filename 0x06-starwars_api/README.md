0x06. Star Wars API General Requirements Allowed editors: vi, vim, emacs All your files will be interpreted on Ubuntu 14.04 LTS using node (version 10.14.x) All your files should end with a new line A README.md file is at the root of the folder of the project Your code should be semistandard compliant. Rules of Standard + semicolons on top. Also as reference: AirBnB style All files are executable The length of files were tested using wc not allowed to use var More Info Install Node 10

$ curl -sL https://deb.nodesource.com/setup_10.x | sudo -E bash - $ sudo apt-get install -y nodejs Install semi-standard Documentation

$ sudo npm install semistandard --global Install request module and use it Documentation

$ sudo npm install request --global $ export NODE_PATH=/usr/lib/node_modules Task Write a script that prints all characters of a Star Wars movie:

The first positional argument passed is the Movie ID - example: 3 = “Return of the Jedi” Display one character name per line in the same order as the “characters” list in the /films/ endpoint You must use the Star wars API You must use the request module
