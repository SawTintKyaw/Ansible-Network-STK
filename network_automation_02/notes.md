username gns3 privilege 15 secret student
ip domain name example.com
ip ssh version 2

crypto key generate rsa

line vty 0 4
 login local
 transport input ssh


