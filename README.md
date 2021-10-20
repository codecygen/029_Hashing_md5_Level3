In this project, instead of storing our password in database as it is, I will be using password hashing method
with an npm package "md5". This is a Level 3 security for storing password in database.

In cryptography, hashing is a much securer method than encryption. Because in encryption, if the hacker can hack into your system and gets your secret key for encryption, he can decode the password in your database. However, hashing does not need a secret key and it is a type of encryption by using complex mathematical operations. Encryption is easy but decoding is almost impossible.

md5
===

It is one of the most renowned mathematical function that is used for password hashing.