# irc_tracker
- This script is a Bash automation tool that automatically sets up and manages an IRC (Internet Relay Chat) server and client environment through a tmux session.

- Running just one command allows you to rapidly create a complex test environment, making it highly valuable for IRC server development, testing, traffic analysis, and demonstrations.

## Dependency
- Docker
- irssi
- tmux

## Use
``` terminal
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
