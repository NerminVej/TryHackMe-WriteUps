### Learn how to use simple tools such as traceroute, ping, telnet, and a web browser to gather information.

## Task 1 Introduction

- Ensure that you understand why these tools fall under active reconnaissance. Launch your AttackBox and ensure that it is ready. You will need it to answer the questions, especially in later tasks.
> No answer needed

## Task 2 Web Browser

- Browse to the [following website](https://static-labs.tryhackme.cloud/sites/networking-tcp/) and ensure that you have opened your Developer Tools on AttackBox Firefox, or the browser on your computer. Using the Developer Tools, figure out the total number of questions.
![](Attachments/questions.png)
> 8

## Task 3 Ping

- Which option would you use to set the size of the data carried by the ICMP echo request?
![](Attachments/packetsize.png)
> -s

- What is the size of the ICMP header in bytes?
![](Attachments/bytes.png)
> 8

- Does MS Windows Firewall block ping by default? (Y/N)
> Y

- Deploy the VM for this task and using the AttackBox terminal, issue the command `ping -c 10 MACHINE_IP`. How many ping replies did you get back?
> 10

## Task 4 Traceroute

- In Traceroute A, what is the IP address of the last router/hop before reaching tryhackme.com?
![](Attachments/lasthop.png)
> 172.67.69.208

- In Traceroute B, what is the IP address of the last router/hop before reaching tryhackme.com?
![](Attachments/lasthopb.png)
> 104.26.11.229

- In Traceroute B, how many routers are between the two systems?
> 26

- Start the attached VM from Task 3 if it is not already started. On the AttackBox, run `traceroute MACHINE_IP`. Check how many routers/hops are there between the AttackBox and the target VM.
> No answer needed

## Task 5 Telnet

- Start the attached VM from Task 3 if it is not already started. On the AttackBox, open the terminal and use the telnet client to connect to the VM on port 80. What is the name of the running server?
> Apache

- What is the version of the running server (on port 80 of the VM)?
> 2.4.10

## Task 6 Netcat

- Start the VM and open the AttackBox. Once the AttackBox loads, use Netcat to connect to the VM port 21. What is the version of the running server?
> 0.17

## Task 7 Putting It All Together

- Ensure that you gain mastery over the different basic yet essential tools we presented in this room before moving on to more sophisticated tools.
> No answer needed

