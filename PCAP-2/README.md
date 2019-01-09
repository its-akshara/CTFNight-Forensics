# Question

What is the IP address of the computer that was browsing websites? Answer in the form flag{IP address}

# Flag
flag{172.16.174.93}

# Solution
One way is to filter by HTTP, and notice the source of all of the GET requests

# Resources
How does Wireshark work?
Filtering packets (contains, http/udp/tcp etc)
What is a GET request? What does it do?