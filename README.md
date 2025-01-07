Instructions to block porn sites on Windows
Download the blocked_sites.txt file

Click the download link for the blocked_sites.txt file in this repository.
Open the Windows hosts file

Click the Start button or press the Windows key.
Type "Notepad" in the search bar, right-click on Notepad and select "Run as administrator." This is necessary to have permissions to edit system files.
Open the hosts file

In Notepad, choose File > Open.
Navigate to the following route:
makefile
Copy code
C:\Windows\System32\drivers\etc\
At the bottom, change the filter from "Text Files" to "All Files."
Select the hosts file and click Open.
Add the URLs to the hosts file

Open the blocked_sites.txt file that you downloaded, and copy all the URLs that appear in it.
Paste the URLs at the end of the hosts file, each on a new line, in the following format:

127.0.0.1 www.sitio1porno.com
127.0.0.1 www.sitio2porno.com

This redirects requests for these URLs to your local machine, blocking their access.
Save changes

Once you've pasted the URLs into the hosts file, save your changes by selecting File > Save.
Restart the browser

Close and reopen your browser for the changes to take effect. Blocked sites will no longer be accessible from your computer.
