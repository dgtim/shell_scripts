# Shell scripts for daily use

See details in the comments

* aaexpires -- AD account expiration checker
* mkbin -- small but an effective shell script creation helper: copies file to ~/bin and set x-bit with one toch
* groupwritable -- sets group permissions in a requested way, useful as a crontab job
* bs -- BASH script starter
* replace_spaces -- replaces spaces in the filename(s) with the dashes
* space -- shortcut for the 'du', including dot files, sorted
* ff -- quick search (=fast find) in the current directory
* shosts -- expands SLURM style node notation like 'xx[1,3,4-6],yy2' into 'xx1 xx3 xx4 xx5 xx6 yy2'
* tfunctions -- bunch of shell functions used for administrative purpose on the cluster
* ipmi -- wrapper for the ipmitool utilities
* racadm -- wrapper for the Dell's idracadm7 utility
* cx -- quick wrapper for the 'chmod'
* tarit -- tar wrapper, again, for the BASH scritpting teaching purpose mainly
* pdsu -- wrapper for Dell's DSU, runs in parallel on the fixed number of nodes, drains and reboots SLURM nodes
* nst -- node status: a read-only utility that outputs node status info incl SLURM state

All of these materails have been used either for the Linux HPC cluster administration purpose or as demo / exsercises for the Linux Shell Basic and Scripting tutorials https://aaltoscicomp.github.io/linux-shell/

See also https://github.com/dgtim/demospace with the collected BASH demos for the scripting tutorial (the link above).
