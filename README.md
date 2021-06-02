# Goldman Sachs Engineering Virtual Program
The course provided me an excellent opportunity to develop an understanding of what it is actually like to work at Goldman Sachs as an engineer in terms of Cyber Security.

## Password Controls and Security Policies

### Overview 
As a governance analyst it is part of your duties to assess the level of protection offered by implemented controls and minimize the probability of a successful breach. You often need to know the techniques used by hackers to circumvent implemented controls and propose uplifts to increase the overall level of security in an organization. Gaining valid credentials gives the attackers access to the organization’s IT system, thus circumventing most of perimeter controls in place.

## Project Objectuve
`What type of hashing algorithm was used to protect passwords?`

`What level of protection does the mechanism offer for passwords?`

`What controls could be implemented to make cracking much harder for the hacker in the event of a password database leaking again?`

Here is a sample data file containing hashes dumped together:

https://github.com/Pramodsheoran599/Goldman-Sachs-Engineering-Virtual-Program/blob/main/password_dump.txt

After the conducted analysis it was determined that organization uses an outdated password hashing algorithm (MD5) which offers very little protection in the event of a password database leaking. It was also determined that the current password policy is not aligned with industry best practices allowing users to have short passwords (6 characters) and reuse usernames as part of passwords. 

# Project Report and Observations 
Completing this task assigned by Goldman Sachs, MD5 and SHA were the two algorithms that I came across. Analysing the passwords and their respective security algorithms used, I narrowed down my observations into this report.

Complete report is available at: 

https://github.com/Pramodsheoran599/Goldman-Sachs-Engineering-Virtual-Program/blob/main/Review%20of%20the%20Password%20Leak%20and%20Policy%20Changes.pdf

## Resources 

https://arstechnica.com/information-technology/2013/05/how-crackers-make-minced-meat-out-of-your-passwords/

https://howsecureismypassword.net/

https://en.wikipedia.org/wiki/Password_cracking#Software

https://en.wikipedia.org/wiki/Salt_(cryptography)

https://hashcat.com
