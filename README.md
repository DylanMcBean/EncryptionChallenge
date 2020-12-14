# EncryptionChallenge
Hey I've made a CTF Encryption challenge. All you need to do is get the flag from the encrypted file.  
the encrypted file is located at: **Encryption/x64/Release/test.txt.pdea**.  
I have named my algorithm PDEA (Pyros Data Encryption Algorithm).  
- The Block size for my algorithm is 576 bits.  
- The Key size for my algorithm is 512 bits.  
Have Fun 😀.  

# How To Execute
To run the algorithm from the terminal you would run it like "*C:>Encryption.exe **Password Encrypting Security File***"
- **Password**: the password to encrypt/decrypt with
- **Encrypting**: either true/false true for encrypting, false for decrypting
- **Security**: a number in the range 1 -> 8. this is the security level you want to decrypt with. this must be the same for encrypting and decrypting a file to work correctly
- **File**: Link to the un-encrypted file. if your decrypting just enter the filename without .pdea
