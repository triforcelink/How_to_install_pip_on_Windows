Instructions from http://stackoverflow.com/questions/4750806/how-to-install-pip-on-windows

For Windows editions of the 64 bit variety:

Download ez_setup.py and run it; it will download the appropriate .egg file and install it for you. (Currently, the provided .exe installer does not support 64-bit versions of Python for Windows, due to a distutils installer compatibility issue

After this, you may continue with:

Add c:\Python2x\Scripts to the Windows path
Open a new (!) DOS prompt. From there run easy_install pip
