# Encrypt-Decrypt
Encryption and Decryption

This project will give you options to Encrypt or Decrypt any type of 
file. First it will ask you the ‘key’ which will be used to Encrypt or 
decrypt and then it will ask you the name of the file to do so.

Filename and key are passed into the function. And then we open the file, read the data and closed the file
using file functions. ‘rb’ in second line represents reading the file byte 
by byte. And the last three lines helps to create/save the encrypted file 
names ‘CC-’ plus the name of the file. 

We used exclusive OR operator to encrypt the function. First, we 
stored all of the data in bytearray. And then we iterated using for loop.
What enumerate is going to do is, it’s going to give us back the index 
value so it’s going to tell us where we are at in the array list and also
going to give us back the actual value at that position. After that I am 
actually changing my value in my data array, to be whatever my value
is when I do the exclusive-or on my key that I passed in. That actually 
going to change data inside my array. And then the file we create below will be the encrypted version.
