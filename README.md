This is a SAP / Bizploit repository.

The script scanTargets.sft is to be used with Onapsis Bizploit, I wrote this to semi automate the setting up of the Bizploit tool
As is noted in the script you need to add the targets into the script and create a separate text file with the targets in.

Then to run Bizploit with the scanTarget.sft file:-

./bizploit -h

bizploit - Open Source ERP Penetration Testing Framework (v1.50)
Usage: bizploit [-d] [-t targets] [-s script] [-o output]
	If executed with no arguments	Starts interactive bizploit shell
	-t targets	Use bizploit targets configuration file.
	-s script	Use bizploit script file.
	-o outconf	Use bizploit output configuration file.
	-d		Enables debugging
	-v		Enables verbose mode
	-c		Check connectors
	-h		You are here.


./bizploit -t scanTargets.sft

and then wait.

You will also note from the folders created when you extract the Bizploit archive that there is a  Scripts folder there are more examples
