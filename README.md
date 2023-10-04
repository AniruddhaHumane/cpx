# cpx
Advance cp command to copy thousands of files and track progress

# Installation
save above file as `cpx` to `/usr/local/bin/cpx`
If you do not have root access, just save it in any folder and add that folder to `PATH` :
`export PATH=$PATH:/home/user_name/scripts/`


# Usage

    cpx source destination

Example:

    cpx /path/to/source/ /path/to/destination/

# sample output
<pre>
cpx ~/source .                                                                          
     Current: 281 Total: 4112 [######                                                 ]  6%  [00:05:52/00:00:00]
</pre>
