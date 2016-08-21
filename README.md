# Swiss-Tournament-Generator

##Purpose of this Database

The Swiss Tournament Generator is a databse which was created as part of the Fullstack Web Developer Nano Degree program from Udacity.The project was to create an application using `Python` and `PSQL` that could effectively conduct a Swiss Style Tournament. The project has a test Database which when run would pass all the checks within the *tournament_test.py* file. Once passed the production database is ready to be utelized.

#Installation

To run the project successfully it is going to require that you download and install some software.

1. `Python 2.7`
2. `Git`
3. `Virtual Box`
4. `Vagrant`

##Installing Python

In your browser, browse to [python/downoads](https://www.python.org/downloads/) >hover your mouse over *Downloads* > A dropdown list will appear with various operating systems.

##Installing Python on Windows

1. From this list select either Windows X86 or Windows X86-64.
2. Once downloaded locate the file in your download file,(or prefered location) double clicking the file and pressing Run when the dialog box pops up.
3. Next select the Install for all usersoption if you are allowing all user's who access your computer, access to the python program then leave this option selected. If you have multiple users and wish to not install python accross all accounts then select the Install just for me option then press Next.
4. Feel free to change the location path however, it is best to leave it as is and simply select 'Next'.
5. Scroll down in the window and find the 'Add Python.exe to Path' and click on the small red 'X' Choose the 'Will be installed on local hard drive' option then press 'Next'.
6. You will notice that the installation will bring up a command prompt window while Python downloads and installs 'Pip'. 
7. 'Pip' is just a package management tool. This will allow you to install all the additional Python packages that are available for download through PyPI (Python Package Index).
8. Once the install is complete press 'Finish'.

##Installing Python on a Mac Machine

1. From the download list at python.org select Mac OSX 64.32 bit installer.
2. A pop up screen will appear for you to select the installers file location, once you have selected the location press the save button.
3. Once the installer package has been downloaded click on the completed download.
4. The installer will promp you to press Continue, until you reach the license agreement.At this point press agree to continue with the install.
5. The install package will then ask you to install a standard instillation, if you are happy with this then click install
Once the install is complete the installer will exit.

##Installing Git

1. In your browser, browse to [git](https://git-scm.com/downloads) and select the download for your operating system.
2. Your download should start automaticaly.
3. A pop up screen will appear for you to select the installers file location, once you have selected the location press the save button.
3. Once the installer package has been downloaded click on the completed download.
4. The installer will promp you to press Continue, until you reach the license agreement.At this point press agree to continue with the install.
5. The install package will then ask you to install a standard instillation, if you are happy with this then click install
Once the install is complete the installer will exit.

##Installing Virtual Box

1. In your browser, browse to [virtual box](https://www.virtualbox.org/wiki/Downloads) and select the download for your operating system.
2. Your download should start automaticaly.
3. A pop up screen will appear for you to select the installers file location, once you have selected the location press the save button.
3. Once the installer package has been downloaded click on the completed download.
4. The installer will promp you to press Continue, until you reach the license agreement.At this point press agree to continue with the install.
5. The install package will then ask you to install a standard instillation, if you are happy with this then click install
Once the install is complete the installer will exit.

##Installing vagrant

1. In your browser browse over to [vagrant] (https://www.vagrantup.com/downloads.html)
2. Your download should start automaticaly.
3. A pop up screen will appear for you to select the installers file location, once you have selected the location press the save button.
3. Once the installer package has been downloaded click on the completed download.
4. The installer will promp you to press Continue, until you reach the license agreement.At this point press agree to continue with the install.
5. The install package will then ask you to install a standard instillation, if you are happy with this then click install
Once the install is complete the installer will exit.

##Final steps for instillation

1. Download the `vm_touranment_master` file which contains amoungst others the following three files:
  * `tournament.py`
  * `tournament.sql`
  * `tournament_test.py`
2. Open terminal:
  * Windows: Use the Git Bash program (installed with Git) to get a Unix-style terminal.
  * Other systems: Use your favorite terminal program.
3. Change to the desired parent directory:
  * Example: `cd Desktop`.
  * and then `/vm_touranment_master/vagrant`.
4. Run vagrant by entering: `vagrant up`.

##Running the vagrant box
1. Log into Vagrant VM by entering: `vagrant ssh`.
2. Move to *tournament* directory by entering: `cd /vagrant/tournament/`.
3. Create the *tournament* database by entering: `psql -f tournament.sql`.

##Running the test database

1. If you would like to test the database against Udacity's criteria, enter: `python tournament_test.py`
2. The test database shouldl finish by printing `Success!  All tests pass!`

##Running production database

1. To run the production database enter `python tournament.py` into the terminal window.
2. The output of the script will be dispalyed in the terminal window (see below).
3. From here make a selection on what you would like to do.
```
    1) Delete all matches.

    2) Delete all players.

    3) Show all Players.

    4) Add a player.

    5) Show player standings.

    6) Record the outcome of a match.

    7) Generate the next Swiss Pairings.

    8) Exit.

    
Select a menu item:
```
##To exit `vagrant`

1. Enter vagrant halt in the terminal window, or in the `virtual box` gui double click on the `virtual machine` and a terminal style window will open.
2. Click on the `exit` (cross) button in the top left(for Mac osx) or top right (windows based) to exit the program.
3. Another window will appear with three options, select `power off the machine` and press `OK` and this will shut down the `virtual machine`.
