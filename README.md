# Password-Cracker
Program creates a password cracker which will be using the Brute Force technique to crack the password of your choice! 

**What is the Brute Force technique?**
Brute Force technique is a technique in which we check all the possible solutions for a problem against the actual solution. For the possible solutions, we will use something called a Wordlist.

**What is a WordList?**
A Wordlist is basically a collection of passwords that we are going to use in a Brute Force attack!
The source of these Wordlists are actually leaked databases that are available over the internet.

**What to expect in this REPO**
We will implement a very simple Wordlist so that you are able to crack very _weak passwords_. 

**What is hashing?**
Developers and hackers usually run a Hash function on your password to transform them into another form which is known as the Hash of the password.

These Hash functions take your password as an input and transform them into a hash. Now if the hash of two inputs by Hash functions ( hash functions like SHA-1 ) are the same then it implies that the two inputs are the same. So this is how they verify whether the password you entered is right or wrong!

Examples of hash functions are SHA-1 and bcrypt. Now SHA-1 shouldn’t be used for storing passwords as it is really fast and hence really easy to Bruteforce.

**The SCENARIO**
Assume you have landed a penetration testing contract and the web app has a vulnerability. You get access to its whole database and you have cloned it.

Now, you discover that the developer that they had was really not aware of how to store the passwords and they have used SHA-1 to hash the passwords!

Now, you are really smart and you know you can Bruteforce the database via a wordlist that you have! Now the Hack begins!
