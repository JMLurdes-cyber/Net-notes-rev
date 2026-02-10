Just like physical networks, cloud networks also need to be protected. Even though we can get some level of protection using **Security Groups** and **Security Lists**.

Both of them are whitelists that filter allowed connections basing themselves on [[INTRODUCTION TO PORTS|ports]], [[INTRODUCTION TO PORTS|protocols]], ranges or rules (like [[FIREWALLS|firewalls]]), the Security *Lists* apply their rules to the whole Private Cloud, while the Security *Groups* are within specific, admin-stated groups within the Private Cloud allowing of control.

So a Security List could be made blocking all access to Bluetooth from the business, while Security Groups could be made if *some* computers within the Private Cloud mustn't be able to connect to the internet.

---
[[DESIGNING THE CLOUD]]
#ports-and-protocols #cloud-computing 
