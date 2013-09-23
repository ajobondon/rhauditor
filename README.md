RedHat auditing tool
-------------------------------------------------

This script very useful when you want to documented your RedHat Linux system. Very handy tool for RedHat engineer,
system implementator, system auditor, etc.



How to install
-------------------

1. Just download this script manually or use git clone.
2. Copy it to your home directory (in your server) and run it.


rhauditor scenarios and option
-----------------------------------

Auditing scenarios :

	1. System auditing.
	2. Disk, partition and directories auditing.
	3. Network auditing.
	4. Packages and repository auditing.

	-h		Show help message.
	-a		Use all auditing scenarios.
	-s <number>	Choose auditing scenario. Ex, if you write "-s 1" (without quotes) it will run scenario number 1 
	-o		With sosreport tool. Default not using sosreport tool for further analysis 


rhauditor usage
-------------------------------------

		rhaudit -s 1 	: Running scenario number 1
		rhaudit -s -o	: Running scenario number 1 and sosreport tool
		rhaudit -a	: Running all scenarios
		rhaudit -o	: Only running sosreport
		

rhauditor file report
---------------------------------------

You can find rhauditor audit result file in the folder you run this script, I highly recommend you to run this script
in your home folder. Rhauditor will summaries audit process into 1 final report file and audit report 
in tarball for details.

If you use sosreport option, rhauditor will produce 3 files. sosreport tarball, detailed audit report tarball and final 
audit summary file. 


need help?
-----------------------------------

You're very welcome to email me. You can find my email in rhauditor script. 

