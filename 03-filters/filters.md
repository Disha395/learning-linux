## Filter commands

111  ls
112  grep firewall ansaconda-ks.cfg
113  grep firewall anaconda-ks.cfg
114  grep -i Firewall anaconda-ks.cfg
115  grep -i firewall < anaconda-ks.cfg
116  ls
117  grep -i firewall *
118  clear
119  ls
120  grep -R SELINUX /etc/*
121  sudo -isudo -i
122  clear
123  cat /etc/passwd
124  clear
125  grep -R SELINUX /etc/*
126  vim /etc/selinux/config
127  cat /etc/selinux/config
128  grep -vi firewall anaconda-ks.cfg //-v is invert matching all text not having firewall in it
129  clear
130  less anaconda-ks.cfg
131  more anaconda-ks.cfg
132  clear
133  head anaconda-ks.cfg
134  tail anaconda-ks.cfg
135  cd /var/log/
136  ls
137  tail -f yum.log  //see real time changes
138  tail -f dnf.log
139  sudo -i
140  cd /var/log/
141  ls
142  cd
143  sudo -i
144  ls
145  grep firewall anaconda-ks.cfg
146  grep Firewall anaconda-ks.cfg
147  grep -i firewall anaconda-ks.cfg  //-i for remove case sensitivity
148  vim anaconda-ks.cfg
149  grep -i firewall anaconda-ks.cfg
150  grep -i firewall < anaconda-ks.cfg //< is input redirection symbol
151  ls
152  grep -i firewall *
153  grep -iR firewall * //-R searches for in directories
154  cp anaconda-ks.cfg devopsdire/mybootingfile.cfg
155  cd devopsdir
156  ls
157  touch mybootingfile.cfg
158  cd
159  cp anaconda-ks.cfg devopsdir/mybootingfile.cfg
160  grep -iR firewall *
161  grep SELINUX /etc/*
162  grep -R SELINUX /etc/*
163  grep -vi firewall anaconda-ks.cfg
164  clear
165  less anaconda-ks.cfg
166  more anaconda-ks.cfg
167  clear
168  head -20 anaconda-ks.cfg
169  tail -20 anaconda-ks.cfg
170  tail -f anaconda-ks.cfg
171  sudo -i
172  cut -d: -f3 /etc/passwd
173  awk -F':' '{print $1}' /etc/passwd 
174  ls
175  touch sample-file.txt
176  vim sample-file.txt
177  sed 's/hello/namaste/g' *.txt //sed is used to replace words in files
178  sed -i 's/hello/namaste/g' *.txt
179  cat sample-file.txt
180  history
