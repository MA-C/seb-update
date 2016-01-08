### 1. INTRODUCTION
<br>
This script was made to update an exam browser called safe exam browser.

<br>

### 2. EXPLOIT
<br>
This script uses an exploit made that refrences a crontab and changes the sudo file.
This exploit gives whatever user that executes it admin instantly.

<br>

### 3. INSTALL
<br>
We use `cURL` to get the update onto the target computer and into a temporary directory, then it is moved into the applications directory and replaces the outdated version.

<br>

### 4. CLEANUP
<br>
We first remove the temporary directory used to store the Java package during install, then we use the command `sed` to remove the target from the sudoers list.

<br>
