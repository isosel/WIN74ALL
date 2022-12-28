# WIN74ALL
A set of tools you can use to make your own virtualbox window 7 machine, for free.

Download link for windows 7 : https://lecrabeinfo.net/telecharger/windows-7-edition-familiale-premium-sp1-x64

TakeOwnershipEx.zip : a tool to give right permissions to modify protected files such as msinfo

WindowsLoader.zip : a tool to activate windows 7 (detected as a virus on windows 10)

/!\ compatible with windows 7 basic home but not enterprise... /!\

upMSInfo32-V1.0-Setup.zip : a tool to modify system information such as manufacturer name, motherboard name, RAM value, ...

-------------------------------------------------------------------------------------------------------------------------------

An other way to download windows 7 is using Vagrant boxes : 

Vagrantfile : to be tested, it's a vagrant box to download a windows 7 virtual machine through Vagrant Cloud

To use this : 
  1. download vagrant from hashicorp and virtualbox
  2. create a directory to put the file into
  3. open a terminal into that directory, such as git bash
  4. vagrant init
  5. vagrant up
  6. wait for the terminal to give you back the prompt
  7. vagrant halt
  8. open virtualbox and launch the window7test_default_xxxx virtual machine
  9. to log into windows user "vagrant" you need to type the password "vagrant" but for azerty keyboard, it's "vqgrqnt", yea... :D

