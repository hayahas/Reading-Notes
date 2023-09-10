# Reading Class 14

1- Define the term “hashing”.

- chopping something into small pieces

2- Explain to a non-technical friend what a hash function does to a password.

- When you create an account online and set a password, the website doesn't keep your actual password. Instead, it uses this special translator and turns your password into a secret code, like "x7#fPq!zY."

3-What does it mean to ‘salt’ a password?

- adding a very long string of bytes to the password

4- What piece of information would a hacker need to access in order to find the ‘salt’ string for your passwords?

- source code

5- How does the Blowfish block cipher handle the increased computation speed of new computers?

- hashes passwords using a version of Bruce Schneier's Blowfish block cipher with modifications designed to raise the cost of off-line password cracking and frustrate fast hardware implementation


6- What are the issue with the two most commong password hashes for Java (“Java password hash” and “Java password encryption”)?

- one uses unsalted hash and the other reversible encryption
