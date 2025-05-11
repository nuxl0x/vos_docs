Installation
===================================

.. important::

  If any of the required installation files are not present during installation the installer will automatically terminate.

In order to install **VOS** on your Linux machine, the first thing that you are required to do is to download the newest release from the `Github repository <https://github.com/nuxl0x/verbose-octo-spork/releases>`_.

After unpackaging the release, you should be just be left with 3 items.

* vos.sh
* configure.sh
* commands (folder)

In order to proceed with installation, you are required to execute the 'configure.sh' script. The recommended way to do this is to go to the file location and run "bash configure.sh". 

After doing this, you simply have to type "Install" into the first prompt and confirm that all the files are present within the same directory as 'configure.sh' by putting 'y' into the second prompt. After that, the installer will take care of the rest.

Both the 'vos.sh' file and the 'commands' folder will be gone, as they have been moved by the installer.

**VOS** is now successfully installed.

In order to uninstall, you just have to either run 'vos uninstall' or re-run 'configure.sh' but select "Uninstall" as the option. It can be within any directory for the uninstallation process, and after uninstallling, you will find the uninstalled 'vos.sh' script and 'commands' folder present within the same directory as 'configure.sh'. This is useful in cases of debugging.
