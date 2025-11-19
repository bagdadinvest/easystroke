Instructions for the End-User
Anyone who downloads this file will need to follow these steps to use it:

1. Download and Extract the File
Bash

# Download the file (replace URL with your link)
wget [URL_TO_YOUR_FILE]/easystroke_portable_package.tar.gz

# Extract the files

tar -xzvf easystroke_portable_package.tar.gz

2. Install the Packages
The user needs to run the installation command that worked for you:

Bash

sudo dpkg -i *.deb
# Fix any dependency issues (if any are still missing on their system)
sudo apt install -f
3. Move the Configuration
Finally, the user needs to move your configuration folder to their home directory.

Bash

mv .easystroke $HOME/
The $HOME/ variable ensures it goes to their specific home folder, regardless of their username.
