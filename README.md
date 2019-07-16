### zGit

- pull all joblib members from IBM http server
- don`t require prerequisites, work out of the box

**Installation**

1.  Copy rexx files to SYSPROC library
2. set URL variable to directory you want to share
3. set IP variable to ip of your HTTP file server
4. set USERLIB variable to your local JOBLIB

**Note**

If you use IBM HTTP server on z/OS based on apache, you must include mvsds module in httpd.conf: [mvsds](http://publib.boulder.ibm.com/httpserv/manual70/mod/mod_mvsds.html)
