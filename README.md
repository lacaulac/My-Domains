1. Installation for webmasters

For Installing the program for your usage, you must take your /etc/hosts and modify it for adding domains.
Upload your modified host you want clients to use, and replace #url in update.sh by the adress of your "pure" modified hosts file.


2. Installation for users of the domains

For installing the domains and website on your Linux/Unix computer, you must download files given by the webmaster. If is the first time you use this program, you must execute save.sh by going with terminal in the folder of files and type "./save.sh" and enter your password. It will make a save of your original domain file (called hosts file by unix). Now you can use update.sh for installing domains by simply typing "./update.sh" and enter your password. If there is a problem with your Internet access or you want to uninstall it, you must restore the save of your domains file by typing "./restore.sh" in the folder of files of MyDomain