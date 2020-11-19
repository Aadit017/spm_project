# spm_project
This is the cipher text exchange program created using java 14 . 
Cipher is an algorithm which is applied to plain text to get ciphertext. It is the unreadable output of an encryption algorithm.

In this program the user is asked for a shift key and the text and is given the choice to either decrypt or encrypt .
The encrypt and decrypt algorithmns can be described as following : -
E_n(x)=(x+n)mod\ 26
(Encryption Phase with shift n)
D_n(x)=(x-n)mod\ 26
(Decryption Phase with shift n)

An example of encrypting the text="abcd" with the shift value of 2 would give an output - cdef
decrypting the same text- cdef with the same shift key would give an output -"abcd"
..
for any such suggestion please make a pull request 
for using the program please fork it from above 
