Arm binaries for Advance-MAME
============================

* Doesn't require X-Windows - run from the console.
* Requires OSS/SDL/Slang libs to be present.

Install
=======
* Untar in any directory, eg, /usr/local/mame.
* Create initial mame config by running:
  ./advmame --defaults

* Don't forget to run ./advcfg to setup the screen resolutions.
* You might need to install the gpm package (sudo apt-get install gpm) for console mouse.

To use: ./advmame <rom name>


Note: If you are not using the default login 'pi', you will need to add the username you are using to the 'video','input' and sudo groups in /etc/groups.
