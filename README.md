# oracle-instant-client-installation-inside-docker
- how to build image

   $ docker build --tag=dbupdate . 
  
- how to run

  docker run -e USERNAME=username -e PASSWORD=password -e [HOST=dbserver.company.com] -e PORT=1521 -e SID=dev dbupate
