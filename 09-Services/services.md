## Services

38  sudo -i
39  systemctl start httpd
40  systemctl status httpd
41  sudo -i
42  systemctl restart httpd
43  exit
44  systemctl enable httpd
45  systemctl status sshd
46  clear
47  systemctl is-active httpd
48  systemctl status httpd
49  systemctl start httpd
50  systemctl status httpd
51  systemctl is-active httpd
52  systemctl is-enabled httpd
53  cat /etc/systemd/system/multi-user.target.wants/httpd.service
