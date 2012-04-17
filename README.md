# Unofficial client for ns2.trifle.net

Console client for secondary dns server service

* Showing listing of zones
* Adding new zones
* Deleting zones
* Showing zone content
* Detecting current real IP address

## USAGE
    triflenet -l
      Gel list of zones on secondary DNS server

    triflenet -a example.com
      Add example.com to secondary DNS server use your current IP as master IP

    triflenet -a example.com -m 8.8.8.8
      Add example.com to secondary DNS server use 8.8.8.8 as master IP

     triflenet -d example.com
       Delete example.com from secondary DNS serve

## OPTIONS
       --help  Print a brief help message and exits.

       --man   Prints the manual page and exits.

       -l, --list
               Print list of domains

       -a, --add=domain
               Add new domain do list with master IP

       -m, ---master=ip address
               IP address of master domain

       -i, --info=zone
               Show zone contents

       -d, --del=zone
               Delete zone

       -s, --slave-ip
               Display address of secondary domain server

       -?, --version
               Show version


## FILES
    $HOME/.triflenet/credentials

If this file exists, then it is taken the data to access the site.

File format: username:password


## LICENCE
License GPLv3+: GNU GPL version 3 or later <http://gnu.org/licenses/gpl.html>.

This is free software: you are free to change and redistribute it.  There is NO WARRANTY, to the extent permitted by law.
