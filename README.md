# Simple-FIM
File Integrity Monitoring working via bash and expect scripting

Оne day, I was given a task - to install in organization (from 50 to 100 servers) FIM  system. After a while , I installed OSSEC. But then met a number of limitations (and a lot of c-code made me sick. I'm lazy =)). I began to think about writing my own FIM-project with my logic. The basis is simple - bash + expect scripting. Type of monitoring - agentless. Systems under monitoring - any AIX, Linux; network hardware - ASA's, switches; windows support will be a little soon. All you need is one server and ssh access to your system. On target systems you have to create account with the rights on read (by default, script will try to begin monitoring under "fim"). For more please see installation.txt.

Updated 10/09/2016: Added Windows support. For more please see installation.txt. 
Updated 17/09/2016: Console for FIM is also available.
