
## Task 1 Walking An Application

- I confirm that I have deployed the virtual machine and opened the website.
> No answer needed

## Task 2 Exploring The Website

- Read the above.
> No answer needed

## Task 3 Viewing The Page Source

- What is the flag from the HTML comment?

The HTML code starts with this comment that contains the location of the first flag.

![](Attachments/first%20comment.png)

Type now "view-source:https://10-10-171-58.p.thmlabs.com/new-home-beta" to get the first flag.

![](Attachments/firstflag.png)
> THM{HTML_COMMENTS_ARE_DANGEROUS}

- What is the flag from the secret link?

We see that there is a "secret-page" located in the HTML code.

![](Attachments/secret%20site.png)

Inside the sides HTML is the flag

![](Attachments/flag2.png)

> THM{NOT_A_SECRET_ANYMORE}

- What is the directory listing flag?

First we need to go to the /assets page to see all the directories

![](Attachments/assets.png)

Then we go on the "flag.txt" file to gain the flag

![](Attachments/flag3.png)

- What is the framework flag?

Check the comment at the end of the code for a website which we can access to gain the framework flag.

![](Attachments/lastcomment.png)

On the website we can go on the "Change Log" and see that there is a file which we can access on /tmp.zip

![](Attachments/Changelog.png)


Enter /tmp.zip in the search bar to download a zip file. This zip file contains a txt file with the last flag in it.

![](Attachments/Final%20Flag.png)

> THM{KEEP_YOUR_SOFTWARE_UPDATED}

