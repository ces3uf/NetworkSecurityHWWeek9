Write Up

I deployed an mhn honeypot on the Google Cloud network. I only deployed one. I had issues with the mhn admin vm, which wasn't allowing http traffic at first, meaning I couldn't actually log in for a while. Then I had issues later on with nmap on my host machine. I resolved this by running it in the mhn admin vm, but I still didn't get many attacks.
I received one attack on the mhn-honeypot-1 honeypot. The protocol was mysqld. I'm not really sure exactly how this happened or even what the attack really was I think I understand the point of honeypots but I'm not sure I really understand this interface and what exactly it's collecting, as well as why I didn't get many attacks.

