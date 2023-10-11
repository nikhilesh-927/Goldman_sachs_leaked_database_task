# Goldman_sachs_leaked_database_task
Goldman sachs leaked database (Forage). In this task they will give you some hashcodes corresponding to the passwords of users and you have to crack those passwords.

# Task_instructions

1. Try to crack the passwords provided in the 'password_dump.txt' file above using available tools like hydra, hashcat etc. or any other tool you wish.
   
2. Assess the 5 asked questions below in relation to the passwords provided (type of hashing algorithm, level of protection, possible controls that could be implemented, password policy, changes in policy)
   
3. Draft an email/memo briefly explaining your findings in relation to controls used by the organization and your proposed uplifts. 

# Asked_questions

1. What type of hashing algorithm was used to protect passwords?
2. What level of protection does the mechanism offer for passwords?
3. What controls could be implemented to make cracking much harder for the hacker in the event of a password database leaking again?
4. What can you tell about the organization’s password policy (e.g. password length, key space, etc.)?
5. What would you change in the password policy to make breaking the passwords harder? 

# Task_Report
Here is the password_dump.txt https://github.com/nikhilesh-927/Goldman_sachs_leaked_database_task/blob/main/password_dump.txt .
In this you will get usernames : hashcodes(passwords are encrypted in haschcodes)

I used this github tool : https://github.com/ikkebr/PyBozoCrack and was able to crack 18 out of 19 passwords.
