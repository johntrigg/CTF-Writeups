**

John Trigg

Login Admin Challenge Writeup 

Flag:

We had to login to an admin account on the OWASP Juice Website. I did this by SQL injection.

Entering " ' or TRUE --" into the username field messes with the SQL database. This apostrophe at the beginning closes out the username field, the or TRUE causes the database to always return true. The -- comments out the rest of the SQL query, which is unimportant for our purposes.

![](https://lh4.googleusercontent.com/b4-du70-WVKQ2aiIOzNqxvyVjeyfyex4HfsMzzPyAy1YOg4P_PiSkGHK6sEzHHi6biKPUwLzdK6EvyyQRGddFSIk34f3rU3uirp-Kr-J5_X5x0MNZrvzRgWGs-snvD_B6IlvKNVI)

  
  
  
  

Doing this logs us in as an admin, solves the challenge, and gives us the flag.

![](https://lh4.googleusercontent.com/y0xoqWlXkqc7M0vvb0TpZ3hcPflCXjVvC6fTsgODexUY2pfqj6gdSmD5jBt_b3zayhho831Pkar82e9_zm0gpz6uJupMMncoSB3yFRbN38DJrydRwhXO2gSvNtHheTSxWXyet-zA)

  

![](https://lh3.googleusercontent.com/0Hco_uUPak9MylgtycponuhInMPKEPWlhxs52Zow5R6pXMBOoD0Fz3yMEXknEKJHC_9YdDQM_cX1cG9QmDFEiCqNUVCT90fYD8Kg_7lO86KSQcdLBdo6n931pt3oZoBa8G5VXPU0)

  
Flag: 690fa3247a99d651e0b26f947baf0b79b4f404a9**