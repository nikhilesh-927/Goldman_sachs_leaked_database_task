[cracked.txt](https://github.com/nikhilesh-927/Goldman_sachs_leaked_database_task/files/12865778/cracked.txt)[cracked.txt](https://github.com/nikhilesh-927/Goldman_sachs_leaked_database_task/files/12865671/cracked.txt)# Goldman_sachs_leaked_database_task
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

List is below :)
<code>
Usernames        Password Hashes                    Passwords        Algorithm Used

experthead     : e10adc3949ba59abbe56e057f20f883e : 123456         : md5
interestec     : 25f9e794323b453885f5181f1b624d0b : 123456789      : md5
ortspoon       : d8578edf8458ce06fbc5bb76a58c5ca4 : qwerty         : md5
reallychel     : 5f4dcc3b5aa765d61d8327deb882cf99 : password       : md5
simmson56      : 96e79218965eb72c92a549dd5a330112 : 111111         : md5
bookma         : 25d55ad283aa400af464c76d713c07ad : 12345678       : md5
popularkiya7   : e99a18c428cb38d5f260853678922e03 : abc123         : md5
eatingcake1994 : fcea920f7412b5da7be0cf42b8c93759 : 1234567        : md5
heroanhart     : 7c6a180b36896a0a8c02787eeafb0e4c : password1      : md5
edi_tesla89    : 6c569aabbf7775ef8fc570e228c16b98 : password!      : md5
liveltekah     : 3f230640b78d7e71ac5514e57935eb69 : qazxsw         : md5
blikimore      : 917eb5e9d6d6bca820922a0c6f7cc28b : (unable to crack)
johnwick007    : f6a0cb102c62879d397b12b62c092c06 : bluered        : md5
flamesbria2001 : 9b3b269ad0a208090309f091b3aba9db : Flamesbria2001 : md5
oranolio       : 16ced47d3fc931483e24933665cded6d : Oranolio1994   : md5
spuffyffet     : 1f5c5683982d7c3814d4d9e6d749b21e : Spuffyffet12   : md5
moodie         : 8d763385e0476ae208f21bc63956f748 : moodie00       : md5
nabox          : defebde7b6ab6f24d5824682a16c3ae4 : nAbox!1        : md5
bandalls       : bdda5f03128bcbdfa78d8934529048cf : Banda11s       : md5

</code>

# Observations

<code>
   [1]. What type of hashing algorithm was used to protect passwords?

   Answer : As of my observation the hashing algorithm used was MD5.



   [2]. What level of protection does the mechanism offer for passwords?

   Answer : The level of protection offered by MD5 is severely compromised. Hackers can easily find collisions within seconds.



   [3]. What controls could be implemented to make cracking much harder for the hacker in the event of a password database leaking again?

   Answer : There are few important controls should be implemented to make cracking much harder :
             i)   Users are using password of any length so will suggest to introduce concept of minimum password length.
             ii)  Special characters , Uppercase letters , Lowercase letters as well as combination of numbers should be used in passwords.
             iii) Salting of passwords should be used.
             iv)  Try to implement more strong hashing algorithms like SHA-256.



   [4]. What can you tell about the organization’s password policy (e.g. password length, key space, etc.)?

   Answer : Two points are mentioned below about organization's password policy : 
            i)   No such regulations for minimum-length passwords.
            ii)  Also there is no rule for using special characters or numbers or upper and lowercase letters.



   [5]. What would you change in the password policy to make breaking the passwords harder?

   Answer :  Below are some necessary changes I will do to make breaking the passwords harder :  
             i)   Length of password must be of minimum 8 characters.
             ii)  At least 2 special characters like @, #, $  must be used in the passwords.
             iii) There should be a tool which checks the password and tells the user whether it is strong or not.
             iv)  Two-step verification may also be useful in protection the account.

<\code>
