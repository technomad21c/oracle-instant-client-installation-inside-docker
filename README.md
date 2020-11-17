# oracle-instant-client-installation-inside-docker

- Purpose
  to run a Python program inside a docker image which connects to remote Oracle database and update data
  It  contains the commands to install Oracle Instant Client on debian docker image.

- how to build image

   $ docker build --tag=dbupdate . 
  
- how to run

  $ docker run -e USERNAME=username -e PASSWORD=password -e [HOST=dbserver.company.com] -e PORT=1521 -e SID=dev dbupate
