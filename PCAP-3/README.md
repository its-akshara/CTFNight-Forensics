# Question
What OS did the person run? Answer in the form flag{OS_Name}, separate the OS and the OS version with an underscore.
For example: flag{Ubuntu_12.10}

# Flag
flag{Windows_7}

# Solution
Follow TCP Stream of any GET request.
Look at the User-Agent - notice the Windows NT 6.1
https://en.wikipedia.org/wiki/Windows_NT
Windows NT 6.1 corresponds to Windows 7

# Resources
What does it mean to follow a stream in Wireshark?
What are the types of HTTP requests?
What does a GET/POST request consist of?
What is Windows NT?

https://docs.google.com/document/d/17OaL269tgcaAFqKuW2Q1NZ1GgdRSbg3py5CgudOLHIQ/edit?usp=sharing