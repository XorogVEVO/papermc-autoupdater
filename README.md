# PaperMC Automatic Update Installer
 
This program is able to automatically download the latest version of papermc and replace the currently installed one.
It uses paper's own api.

How to set up:

1. Create a file named "autoupdate-path.txt" in the server folder with the filepath of the server jar. (e.g. "/home/xorog/Server/server.jar")

2. Create a file named "autoupdate-version.txt" in the server folder with the version you want. This is most likely the version your server uses. (You need to update this for new minecraft versions) (e.g. "1.16.2")

(optional) 3. Add the updater in your starting-script.

How to run:

**You need .NET Core installed on your machine (https://dotnet.microsoft.com/download).** It runs on Windows, Linux and Mac.
The working directory has to contain the previous mentioned files.
