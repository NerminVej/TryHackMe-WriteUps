### Learn about the essential tools for passive reconnaissance, such as whois, nslookup, and dig.

## Task 1 Introduction

- This room does not use a target virtual machine (VM) to demonstrate the discussed topics. Instead, we will query public WHOIS servers and DNS servers for domains owned by TryHackMe. Start the AttackBox and make sure it is ready. You will use the AttackBox to answer the questions in later tasks, especially tasks 3 and 4.
> No answer needed

## Task 2 Passive Versus Active Recon

- You visit the Facebook page of the target company, hoping to get some of their employee names. What kind of reconnaissance activity is this? (A for active, P for passive)
> P

- You ping the IP address of the company webserver to check if ICMP traffic is blocked. What kind of reconnaissance activity is this? (A for active, P for passive)
> A

- You happen to meet the IT administrator of the target company at a party. You try to use social engineering to get more information about their systems and network infrastructure. What kind of reconnaissance activity is this? (A for active, P for passive)
> A

## Task 3 Whois

- When was TryHackMe.com registered?
> 20180705
![](Attachments/creation.png)
- What is the registrar of TryHackMe.com?
![](Attachments/registrar.png)
> namecheap.com

- Which company is TryHackMe.com using for name servers?
> Cloudflare.com

## Task 4 nslookup and dig

