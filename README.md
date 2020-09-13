# NODEJS_NPM_INSTALLATION

* Installation script for Nodejs npm  for linux ubuntu.
* Download the script.

` ` ` sudo ./nodejs_npm.sh ` ` `

Run the script with sudo.
change the file permission with 777

` ` ` sudo chmod 777 nodejs_npm.sh ` ` `

## Prerequisite:

   * Ubuntu OS.
## Note:

* **you can choose the node versions by replacing the exixting version in the shell script line no: 21 i.e "setup_8.x" to "setup_12.x or setup_iojs_1.x".Replace by your needed versions.**

     curl -sL https://deb.nodesource.com/ **setup_8.x** | sudo -E bash 
    
    
 ## Nodejs and NPM Versions:
   
   **"Version URL for Download"** is used for refernce to change the versions in shell script to install respective versions you need. 
    
   Node Versions   | Version URL for Download | NPM Verson
   ----------------|--------------------------|------------
   Node version 14 | setup_14.x | 6.14
   Node version 13 | setup_13.x | 6.13  
   Node version 12 | setup_12.x | 6.13
   Node version 11 | setup_11.x | 6.7
   Node version 10 | setup_10.x | 6.14
   Node version 9  | setup_9.x  | 5.6
   Node version 8  |setup_8.x   | 6.13
   Node version 7  | setup_7.x  | 4.2
   Node version 6  | setup_6.x  | 3.10
   Node version 5  | setup_5.x  | 4.6
   Node version 4  | setup_4.x  | 2.15
   Node version 3  | setup_iojs_3.x  | 2.14
   Node version 2  | setup_iojs_2.x  | 2.13
   Node version 1  | setup_iojs_1.x  | 2.9
