# svn

# 1.create project 
  makedir /data/svn/test

# 2.add file path to svn
 svnadmin create /data/svn/test
 
# 3.configure your svnserve.conf

# 4.restart svn service
  kill -9 PID
  svnserve -d -r /data/svn/
  
