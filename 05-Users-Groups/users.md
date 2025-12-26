## Users and Groups

39  head -1 /etc/passwd
40  grep vagrant /etc/vagrant
41  grep vagrant /etc/passwd
42  cat /etc/group
43  grep vagrant /etc/group
44  id vagrant
45  clear
46  unseradd ansible 
47  useradd ansible
48  useradd aws //to add user
49  useradd jenkins
50  tail -4 /etc/passwd9
51  tail -4 /etc/passwd
52  tail -4 /etc/group
53  id ansible
54  groupadd devops
55  usermod -aG devops ansible
56  id ansible //shows info about user
57  grep devops /etc/group
58  vim /etc/group
59  id aws
60  passwd ansible
61  passwd aws
62  passwd ansible
63  passwd jenkins
64  su - ansible
65  last
66  who
67  lsof -u vagrant //what user accessed what files , here vagrant is user
68  userdel aws //deletes without deleting home directory
69  ls /home/
70  userdel -r jenkins // -r deletes home dir too
71  ls /home/
72  groupdel devops
73  userdel -r ansible
74  rm -rf /home/aws
75  ls /home/
76  history
