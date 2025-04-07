# Installing Python and PyCharm

In order to user Python with PyCharm, you will first have to install both piece of software. Although you will be using 
them in tandem, Python and Pycharm are separate pieces of software made by separate organisations. As such, they will need to be installed separately.

COMP-1510 requires using specific installation options which are easily missed. As such, this page will cover how to
properly install Python and PyCharm the first time.

The screenshots in this document will show the installers for Windows. The UI will be slightly different on other
operating systems, but the overall process will be the same.

## Installing Python

Most Linux distributions should already come with an upto date Python interpreter, but Windows doesn't have one by default and Mac come packaged an outdated version.

1. Go to the official Python [download page](https://www.python.org/downloads/) on the computer you want to install Python to.

2. The website should automatically detect your operating system and change the main download button to the correct version of the installer. If the auto detection is not correct, click one of the options below to manually select the version.
![](img/installation/python-download.png)

3. Go to the folder where the file was downloaded to and click on it to begin installation.

4. Check the box labelled `Add python to PATH`, to make Python more easily accessible on your terminal, and then click `Install Now`.
![](img/installation/python-installer1.png)

5. Wait for the installer to finish.
![](img/installation/python-installer2.png)

6. Click `Close` when the installation is complete.
![](img/installation/python-installer3.png)

## Installing PyCharm

One mistake students often make when installing PyCharm is selecting the wrong version.
In COMP-1510, students should use PyCharm Professional, not PyCharm Community. PyCharm Professional requires a license
to use, which BCIT students receive for free.

1. Go to the [PyCharm download page](https://www.jetbrains.com/pycharm/download/) on the computer you want to install PyCharm to.

2. PyCharm Professional supports Windows, Mac, and Linux, and the website should automatically detect your operating system. If it is incorrect, click on the correct one from the choices just below the header.

3. The website should also automatically detect the architecture of your computer and select the correct version of the installer, but if it is incorrect, click the dropdown beside the `Download` button and select the correct version.
![](img/installation/pycharm-download.png)

4. Click the `Download` button to download the installer.

5. Go to the folder where the file was downloaded to and click on it to begin installation. It's a large file so it's normal for it to take a few seconds to load.

6. Click next for the next two screens.
![](img/installation/pycharm-installer1.png)
![](img/installation/pycharm-installer2.png)

7. It is recommended to check the boxes for `Open folder as project` and `Associate .py files`, as these will allow for quicker access to PyCharm. Then click next.
![](img/installation/pycharm-installer3.png)


8. Click install.
![](img/installation/pycharm-installer4.png)

9. Wait for the installation to complete.
![](img/installation/pycharm-installer5.png)

10. Check the box labelled `Run PyCharm` and then click `Finish`. The newly installed PyCharm will open.
![](img/installation/pycharm-installer6.png)

11. Check the box for agreeing to the user agreement and click `Continue`
![](img/installation/init1.png)

12. Choose whether to send usage statistics to Intellij.
![](img/installation/init2.png)

13. Click `Free 30-Day Trial` for now, we will activate the license in the Configuration section.
![](img/installation/init3.png)

14. If the installation was successful, you should see this landing screen:
![](img/installation/init4.png)

## Next Steps
If you have followed these steps successfully, the PyCharm IDE should already be open in front of you.
Proceed to [Configuration](configuration.md) to set up the IDE for use in COMP-1510.