PyCharm
# git project
## io network
---------------------------------------
INSTALLATION INSTRUCTIONS
===============================================================================


logic exercise
  Linux Installation Instructions
  ------------------------------------------------------------------------------
  1. Unpack the PyCharm distribution archive that you downloaded to
     where you wish to install the program. We will refer to this destination
     location as your {installation home} below.

  2. Open a console and cd into "{installation home}/bin" and type:

       ./pycharm.sh

     to start the application. As a side effect, this will initialize various
     configuration files in the ~/.PyCharmCE2019.3 directory.

  3. [OPTIONAL] Add "{installation home}/bin" to your PATH environment
     variable so that you may start PyCharm from any directory.

  4. [OPTIONAL] To adjust the value of the JVM heap size, create
      ~/.PyCharmCE2019.3/config/pycharm.vmoptions (or pycharm64.vmoptions
      if using a 64-bit JDK), and set the -Xms and -Xmx parameters. To see how
      to do this, you can reference the vmoptions file under
      "{installation home}/bin" as a model.

  [OPTIONAL] Changing the location of "config" and "system" directories
  ------------------------------------------------------------------------------
  By default, PyCharm stores all your settings under the ~/.PyCharmCE2019.3/config
  directory and uses ~/.PyCharmCE2019.3/system as a data cache.
  If you want to change these settings,

  1. Open a console and cd into ~/.PyCharmCE2019.3/config

  2. Create the file "idea.properties" and open it in an editor. Set the
     idea.system.path and/or idea.config.path variables as desired, for
     example:

     idea.system.path=~/custom/system
     idea.config.path=~/custom/config

  3. Note that we recommend to store data cache ("system" directory) on a disk
     with at least 1GB of free space.


Enjoy!


modify Alex
-PyCharm Development Team
