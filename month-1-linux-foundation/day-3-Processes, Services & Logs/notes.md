Process: it is a program that runs on linux it can be run by users or system, like, python app.py, ls, etc.
After execution process dies

Services: It is a long running program that runs when system starts and it is mostly runs in background. Ex: ssh, docker, etc.

Logs: logs are the data entry everything that happens in linux is managed on logs, it is importandt to understand and read logs its easy human readable language(mostly english) and it can help in identifying thread and risk.

logs storage path /var/log/

/var/log/auth.log : It contains all the logins, ssh, login failure, etc 
/var/log/syslog : it contains service message, kernal event and errors
