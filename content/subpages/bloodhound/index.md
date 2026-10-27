---
title: "Bloodhound"
_build:
  list: never
---

The latest way you can use bloodhound (as of 27/10/26) is by installing `bloodhound-cli`  
Installation steps: https://bloodhound.specterops.io/get-started/quickstart/community-edition-quickstart  
another tool that greatly compliments bloodhound is a tool called `AD-Miner`, for usage and installation visit: https://github.com/AD-Security/AD_Miner  

## Process

**Step 1:**
```
sudo bloodhound-python -d MARVEL.local -u fcastle -p Password1 -ns 192.168.138.136 -c all

-d is for domain
-u is for user
-p is for password
-ns is for nameserver, i.e., domain controller's ip
-c is for "what are we collecting?"..we are collecting everything

```

this collected the data..
![Pasted image 20251201141933](images/Pasted-image-20251201141933.png)


**Step 2:**
Imported this in bloodhound and ...

![Pasted image 20251201213620](images/Pasted-image-20251201213620.png)
