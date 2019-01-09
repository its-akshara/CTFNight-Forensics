# Question
Try to find the password! The flag format should be flag{password_here}.

# Hint
The password may be URL encoded

# Flag
flag{KN1Z6PXVy9}

# Walkthrough
Look at the POST requests, follow the TCP stream.
Notice that there is userid=spiveyp&pswrd=S04xWjZQWFZ5OQ%3D%3D
This is URL encoded, which ends up becoming S04xWjZQWFZ5OQ==
This is the base64 of the password

# Resources
URL encoding