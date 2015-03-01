<h3>Python Keylogger</h3>
This is a basic keylogger written in Python. The script imports the following libraries:
<ul>
<li><strong>win32api</strong> - Available at <a href="http://sourceforge.net/projects/pywin32/">http://sourceforge.net/projects/pywin32/</a></li>
<li><strong>win32console</strong> - Installed with Python by default</li>
<li><strong>win32gui</strong> - Installed with Python by default</li>
<li><strong>pythoncom</strong> - Available at <a href="http://sourceforge.net/projects/pywin32/">http://sourceforge.net/projects/pywin32/</a></li>
<li><strong>pyHook</strong> - Available at <a href="http://sourceforge.net/projects/pyhook/">http://sourceforge.net/projects/pyhook/</a></li>
</ul>

If you're using a version of Python more recent than 2.7, do not use the link above for pyHook. I was only able to find this library for Python 2.7.

<h4>Install & Use</h4>
To use this keylogger, you must have Python 2.7 installed as well as a text file with the same name and location defined on the following line:<br />
`f=open('c:\output.txt','r+')`
<br />
Download the keylogger.py script and run it using the following command:<br />
`python /path/to/file/keylogger.py`
<br />
This will run it in the background and save everything to the output.txt file.
