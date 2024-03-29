Reproduction Steps
1.	Ensure that usr/local/bin is user writable. (See Appendix C to see how to install Homebrew to make this happen)
2.	Open a new terminal in macOS and change to the directory that POC_README.txt and reverse_shell.sh files are located in.
3.	Execute in the terminal: mv reverse_shell.sh /usr/local/bin/diskimagetool && chmod a+x /usr/local/bin/diskimagetool 
4.	Go to the application “Feedback Assistant”
5.	Log into the application with your Apple ID
6.	Click “New Feedback”
7.	Select “macOS”
8.	Select “Time Machine, Suggestion, and Something else not on this list.
9.	Click “Get macOS Time Machine Logs” at the bottom.
10.	Wait approximately 1-2 minutes for a reverse shell to appear.
11.	Run the command `whoami` and observe you are root.
