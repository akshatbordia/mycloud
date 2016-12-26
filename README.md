# MyCloud
MyCloud is a storage cloud created on the internal network of my college with the help of owncloud and on Ubuntu OS.

Technology:-
OS - Ubuntu

Repository/Tools Required:- 
Owncloud 16.04
Apache Server
Sqlite
Collobora CODE for Office support in cloud

Installation:-
You have add the repository key to apt. Keep in mind that the owner of the key may distribute updates, packages and repositories that your system will trust. Run the following shell commands as root to trust the repository:
1. wget -nv https://download.owncloud.org/download/repositories/stable/Ubuntu_16.04/Release.key -O Release.key
2. sudo apt-key add - < Release.key

Run the following shell commands as root to add the repository and install from there.

3. sudo sh -c "echo 'deb http://download.owncloud.org/download/repositories/stable/Ubuntu_16.04/ /' > /etc/apt/sources.list.d/owncloud.list"
4. sudo apt-get update
5. sudo apt-get install owncloud

Facility provided:-
1. Office Support
2. email connect - get all your mails in it
3. Notes
4. Calender
5. contacts
6. task
7. Apps support for android

License -
GNU General Public License
Apache License 2.0
