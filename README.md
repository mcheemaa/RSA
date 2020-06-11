# RSA

In this project we create a ReallyLongInt class as the built in data types are not large enough for the security of the cryptography. We use unit testing to make sure we cover all the edge cases and that our code is working as it should be. As we are making a new data type we have to make all the needed functions for it including the basic operators for a number and other function calls like isPrime or even. We then use the data structure and follow the cryptography algorithm to create a public key set and a private key set to make sure it is always secured. In this kind of cryptography, we generate matched pair of keys: the public key and the private key. The public key can be used to encrypt a message, but cannot be used to decrypt the message it encrypts. Only the private key can be used to decrypt messages encrypted using the public key. So, the public key can be transmitted freely, with little danger of compromising security. Therefore, this makes this kind of encrypting and decrypting technique very useful. 

You can compile all of them using the command. “Make”

You can run each of them like this. 

./ReallyLongInt_TEST

./numberTheory_TEST

./keygen 3 3 (give two comman line paramters) numbers 

./encrypt encrypt.txt message.txt output.txt (give 3 files)

./decrypt decrypt.txt message.txt output.txt (give 3 files)



Problems:

Pretty much everything works except some slight issues with the decrypt method.

Coverage: 85 / 84.4
