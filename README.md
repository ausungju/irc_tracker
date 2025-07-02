# irc_tracker

``` bash
$ ./irc_tracker -h
Usage: ./irc_tracker [-f executable_file] [-p password] [-h]

  -f FILE      Path to the IRC server executable (default: Docker-based InspIRCd server)
  -p PASSWORD  IRC server connection password (default: None; ignored if -f is not specified)
  -h           Show this help message 

ex:
  ./irc_tracker
  ./irc_tracker -f ./ircserv
  ./irc_tracker -f ./ircserv -p <PASSWORD>

```
