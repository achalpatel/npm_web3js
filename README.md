# npm_web3js
Installing web3js using npm install.
This guide is only for windows

Hello,
I want to write a guide for installing web3js using npm install.
While I was installing web3js using npm, I was getting errors related to package-json, modules not found, throw err, etc.
So if you are facing such errors, here is the guide that worked for me.

1. Download nodejs installer from the website.  https://nodejs.org/en/
2. Install nodejs with default options selected. Most important is to check the option asking for installing all essential files like python, c++. So after the nodejs is installed, wait for a while and Powershell will pop up and continue installing essential libraries.
3. Open command prompt from location : pathofnodejsfolder/
4. 
    npm install --upgrade request,  
    npm install --upgrade mkdirp,  
    npm install web3  
   (I was facing vulnerability errors when I was performing npm install web3. But when I tried to upgrade mkdirp and request, it worked.) 

I hope it works! Thank you.
