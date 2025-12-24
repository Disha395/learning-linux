## I/O Redirection 
2  uptime
3  uptime > /tmp/sysinfo.txt // '>' is input redirection symbol for program to file
4  cat /tmp/sysinfo.txt
5  ls
6  ls > /tmp/sysinfo.txt
7  cat /tmp/sysinfo.txt
8  uptime >> /tmp/sysinfo.txt
9  cat /tmp/sysinfo.txt
10  clear
11  free -m
12  df -h
13  echo "Guten Tag" //echo used to print stuff
14  ls
15  cat /dev/null > sample-file.txt // '/dev/null' is like black hole of file , nothing comes out
16  cat sample-file.txt
17  free -m > dev/null
18  freeeee -m 2>> sample-file.txt // 2 for standard error , 1 for default output
19  cat sample-file.txt
20  freeeee -m &>> sample-file.txt // '&' for both output and error
21  cat sample-file.txt
22  cd /var/log/
23  ls
24  cd
25  wc -l /etc/passwd //counts number of lines
26  cd /etc
27  ls | wc -l
28  ls | grep host
29  tail /var/log/messages | grep vagrant //piping is used for program to program redirection 
30  free -m | grep Mem
31  find /etc -name host*
32  clear
33  yum install mlocate
34  updatedb
35  locate host
36  cd
37  history
