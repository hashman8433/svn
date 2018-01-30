# svn

* create project 

    makedir /data/svn/test

* add file path to svn

    svnadmin create /data/svn/test
 
* configure your svnserve.conf

* restart svn service

    kill -9 PID 
  
    svnserve -d -r /data/svn/
  
