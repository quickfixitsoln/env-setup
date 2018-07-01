# env-setup
Please follow below instructions to setup the virtual machines:

  1. Download and install vagrant:

    windows:     https://releases.hashicorp.com/vagrant/2.1.1/vagrant_2.1.1_x86_64.msi
    mac:  https://releases.hashicorp.com/vagrant/2.1.1/vagrant_2.1.1_x86_64.dmg

 2. Download and install virtual box:
      windows:          http://download.virtualbox.org/virtualbox/5.1.6/VirtualBox-5.1.6-110634-Win.exe
      mac or other:  http://download.virtualbox.org/virtualbox/5.1.22/VirtualBox-5.1.22-115126-OSX.dmg


 3. Download this github repo and extract the zip file.

    https://github.com/quickfixitsoln/env-setup.git

4. Download and install GITBashshell , open git bash shell
      
      cat ~/.ssh/config << ServerAliveInterval 20
         

5. Restart the machine and press F2 or F10 to go into Bios mode. VT-x/AMD-v virtualization must be enabled in BIOS
6.  open git bash shell and go into the unzipped multivagrant directory:

     #cd  dir-of-multi-vagrant
      #vagrant up gitlab.example.com
     
          

 7. Enter ip address through putty:
       #vagrant ssh gitlab.example.com
         username /password :  vagrant/vagrant
         Sudo -i
  
