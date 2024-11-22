 cd /opt/081024_morning/
  987  ll
  988  cd /opt/081024_morning/dima2024
  989  touch test.txt
  990  chmod u+x,o-r test.txt
  991  l
  992  ls
  993  ll
  994  cd /opt/081024_morning/dima2024
  995  ps -ef
  996*
  997  ps -ef | wc -l
  998  ps -ef | tail -n+2
  999  ps -ef | tail -n+2 | wc -l
 1000  ps -ef
 1001  ps -ef | tail -n+2 | wc -l >> ps.txt
 1002  history
 1003  cat ps.txt
 1004  history
[ec2-user@ip-172-31-33-20 dima2024]$
