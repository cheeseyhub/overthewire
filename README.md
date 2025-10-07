# Notes

*** Level 13  *** - 
requires ssh -i to use the private key to log onto the localhost port

** Level 14 *** - 
nc (netcat) is used to send packets of data. Its syntax is nc host port < filename 

** Level 15 *** - 
openssl s_client can be used to connect to a server with tls and ssl protocol. Its syntax is openssl s_client -connect server:port

** Level 16 *** -
nmap -p min-max  can be use to find ports. use -quiet flag on openssl s_client to get rid of the done and keyupdate errors.

** Level 18 *** -
ssh with the -t flag can be used to run commands on the remote server using quotations and && sign to combine commands

** Level 19 *** - 
chmod u+s sets the 's' bit on the permissions for the user so now when a user executes the file it is executed as the owner of the file.
