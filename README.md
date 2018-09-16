# HyperledgerFabricInstallation
A detailed guide to install hyperledger fabric

OS used : UBUNTU 18.04

Issues : After multiple attempts to install fabric in ubuntu 16.04 due to non complatibility issues
and different versions of npm I upgraded to 18.04 and tried the same but docker was not able to 
access the files as the user  group permission had only been given read permission hence by using 
the chmod command i was able to change permissions and succesfully install fabric.

GO to https://hyperledger-fabric.readthedocs.io/en/release-1.2/install.html
to install fabric .


1. Create a directory in home . 

2. Clone the github repo using curl  into the specified directory

3. Elevate persisions to the giveen folder by issuing the command $chmod u+w myfolder

4. Go to the cloned folder then issue the command docker images . 

https://user-images.githubusercontent.com/28874545/45598960-4333c500-ba01-11e-9ef3-26de82cb835c.png
