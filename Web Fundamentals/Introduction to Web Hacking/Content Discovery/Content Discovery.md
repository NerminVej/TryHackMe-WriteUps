### Learn the various ways of discovering hidden or private content on a webserver that could lead to new vulnerabilities.

## Task 1 What Is Content Discovery?

- What is the Content Discovery method that begins with M?
> Manually

- What is the Content Discovery method that begins with A?
> Automated

- What is the Content Discovery method that begins with O?
> OSINT

## Task 2 Manual Discovery - Robots.txt


- What is the directory in the robots.txt that isn't allowed to be viewed by web crawlers?

First we go to the specified webpage which is /staff-portal.

![](Attachments/staffportal.png)

> /staff-portal

## Task 3 Manual Discovery - Favicon


We input the above mentioned command to get a hash.

![](Attachments/the%20has.png)

With that hash we can search the OWASP_favicon_database

![](Attachments/the%20database.png)

> cgiirc


## Task 4 Manual Discovery - Sitemap.xml


- What is the path of the secret area that can be found in the sitemap.xml file?

Check the source code of the site out that is mentioned.

> /s3cr3t-area

- What is the flag value from the X-FLAG header?

## Task 5 Manual Discovery - HTTP Headers

Run the above mentioned command with the -v flag.

> THM{HEADER_FLAG}

## Task 6 Manual Discovery - Framework Stack


- What is the flag from the framework's administration portal?

We go on the static-labs site that TryHackMe provides to then go to the documentations page to gain the /thm-framework-login path. We use that on the machines IP address to gain this flag.

> THM{CHANGE_DEFAULT_CREDENTIALS}

## Task 7 OSINT - Google Hacking / Dorking

We can utilize Google's advanced search engine features to pick out custom content.

- What Google dork operator can be used to only show results from a particular site?
> site:

## Task 8 OSINT - Wappalyzer

- What online tool can be used to identify what technologies a website is running?
> wappalyzer


## Task 9 OSINT - Wayback Machine

With The Wayback Machine we can show us old pages of the internet.

- What is the website address for the Wayback Machine?
> https://archive.org/web/

## Task 10 OSINT - GitHub

- What is Git?
> Version Control System

## Task 11 OSINT - S3 Buckets

- What URL format do Amazon S3 buckets end in?
> .s3.amazonaws.com

## Task 12 Automated Discovery

- What is the name of the directory beginning "/mo...." that was discovered?

With the help of the gobuster command we can gain the directories.

> /monthly

- What is the name of the log file that was discovered?
> /development.log
