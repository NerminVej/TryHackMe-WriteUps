### Learn how to use Repeater to duplicate requests in Burp Suite

## Task 1 Introduction Outline

- _**Note:** If you are not using the AttackBox and want to connect to this machine without the VPN, you can do so using this link once the machine has fully loaded and an IP address is displayed:_ [https://LAB_WEB_URL.p.thmlabs.com](https://LAB_WEB_URL.p.thmlabs.com)_._
> No answer needed

## Task 2 Repeater What is Repeater?

- Familiarise yourself with the Repeater interface.
> No answer needed

## Task 3 Repeater Basic Usage

- Practice modifying and re-sending the request numerous times.
> No answer needed

## Task 4 Repeater Views

- Experiment with the available view options.
> No answer needed

- Which view option displays the response in the same format as your browser would?
> Render

## Task 5 Repeater Inspector

- Get comfortable with Inspector and practice adding/removing items from the various request sections.
> No answer needed

## Task 6 Practical Example

- Capture a request to `MACHINE IP` in the Proxy and send it to Repeater.
> No answer needed

- Try viewing this in one of the other view options (e.g. Rendered).
> No answer needed

- Send the request. What is the flag you receive?

We send the "FlagAuthorised: True" request to gain the flag.

![](Attachments/flag1.png)

> THM{Yzg2MWI2ZDhlYzdlNGFiZTUzZTIzMzVi}

## Task 7 Practical Challenge

- Capture a request to one of the numeric products endpoints in the Proxy, then forward it to Repeater.
> No answer needed

- What is the flag you receive when you cause a 500 error in the endpoint?
> THM{N2MzMzFhMTA1MmZiYjA2YWQ4M2ZmMzhl}


## Task 8 Extra Mile SQLi with Repeater

- Let's start by capturing a request to MACHINE IP in the Burp Proxy. Once you have captured the request, send it to Repeater with `Ctrl + R` or by right-clicking and choosing "Send to Repeater".
> No answer needed

- You should see that the server responds with a "500 Internal Server Error", indicating that we successfully broke the query:
> No answer needed

- With this information, we can skip over the query column number and table name enumeration steps.
> No answer needed

- Looking through the returned response, we can see that the first column name (`id`) has been inserted into the page title:
> No answer needed



## Task 9 Conclusion Room Conclusion

- I can use Burp Suite Repeater!
> No answer needed

