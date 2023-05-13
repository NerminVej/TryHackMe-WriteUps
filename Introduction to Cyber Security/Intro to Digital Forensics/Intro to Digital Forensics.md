### Learn about digital forensics and related processes and experiment with a practical example.

## Task 1 Introduction To Digital Forensics

- Consider the desk in the photo above. In addition to the smartphone, camera, and SD cards, what would be interesting for digital forensics?

> Laptop

## Task 2 Digital Forensics Process

- It is essential to keep track of who is handling it at any point in time to ensure that evidence is admissible in the court of law. What is the name of the documentation that would help establish that?
> Chain of Custody

## Task 3 Practical Example of Digital Forensics

We use the pdfinfo command to gain more intel about the ransom-letter.pdf file and find out who the author of the file is.

![](Attachments/Info%20about%20the%20pdf.png)

- Using `pdfinfo`, find out the author of the attached PDF file.
> Ann Gree Shepherd

With the help of the command exiftool we are able to gain the GPS position of where the foto was taken.

![](Attachments/GPS%20Location-1.png)

![](Attachments/Milk%20Street.png)


- Using `exiftool` or any similar tool, try to find where the kidnappers took the image they attached to their document. What is the name of the street?
> Milk Street

We can find the canon model name with the exiftool command

![](Attachments/Canon%20Model.png)

- What is the model name of the camera used to take this photo?
> Canon EOS R6


