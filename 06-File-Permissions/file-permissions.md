## File Permisions

77  ls -l
78  mkdir /opt/devops
79  ls -l /opt/
80  groupadd devops
81  useradd ansible
82  useradd jenkins
83  useradd aws
84  useradd miles
85  vim /etc/passwd
86  vim /etc/group
87  id ansible
88  ls -ld /opt/devopsdir
89  ls -ld /opt/devops
90  chown -R ansible:devops /opt/devops 
91  ls -ld /opt/devops
92  chmod o-x /opt/devops
93  ls -ld /opt/devops
94  chmod o-r /opt/devops
95  chmod g+w /opt/devops
96  ls -ld /opt/devops
97  su - miles
98  su - aws
99  mkdir /opt/webdata
100  ls -ld /opt/webdata
101  chown aws,devops /opt/webdata
102  chown aws.devops /opt/webdata
103  ls -ld /opt/webdata
104  chmod 770 /opt/webdata // 4-read 2-write 1-execute
105  ls -ld /opt/webdata
106  history
