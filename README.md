Theos-Installation
==================

These packages install Theos to your iDevice and OS X computer. Mostly for developer use and such.

To install Theos, you must do so on both your Mac and your Device. Move the file TheosInstallDevice to your device at /usr/bin using SSH or using iFunbox. Make sure you have BigBoss Recommended Tools installed on your device. Once you have moved the TheosInstallDevice to /usr/bin, use the command <pre>chmod a+x TheosInstallDevice</pre>. Then, execute the command by typing in <pre>TheosInstallDevice</pre>. To install on your Mac, navigate to the directory where you saved it using the <pre>cd</pre> command and then, just use the <pre>chmod a+x TheosInstallMac</pre>. Execute the Command by typing in <pre>./TheosInstallMac</pre>. 

To use Theos, just execute the command <pre>$THEOS/bin/nic.pl</pre> on your Mac and then, once you have created a project and have coded it, navigate to the project directory and type <pre>make package</pre>. Once that command is finished, type <pre>make install</pre> and it will install it to your device for testing.
