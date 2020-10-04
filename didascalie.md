# Comandi didascalici

## Man

*man $command*

Mostra il manuale relativo al comando che segue.

**sam-sepi@home:~$** *man whois*

*man -k $command* mostra una descrizione sommaria del comando. Alias di *whatis $command*

**sam-sepi@home:~$** *man -k netcat*

*netcat (1)           - TCP/IP swiss army knife*

## Where is, what is and who is

*whatis $command* alias di *man -k $command*. Restituisce una descrizione sommaria del comando.

*whereis $command* restituisce la locazione del file e del relativo manuale

**sam-sepi@home:~$** *whereis netcat*

*netcat: /usr/bin/netcat /usr/share/man/man1/netcat.1.gz*

*whois $host* client per il servizio di directory *whois*


