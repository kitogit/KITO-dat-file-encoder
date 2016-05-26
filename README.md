# KITO-dat-file-encoder
Encodes and decodes dat files with checksum

## Revision 8

Presenting our basic tool for decryption and encrypting .dat files for IT  
Revision 2: The basics and first public release.  
Revision 3: Added ability to change the xor key by demand! A hash table is used to cache the used to decode/encode faster by reusing values. And progress status added  
Revision 4: Added preChecksum and postChecksum and fixed KITO header to .dat files. Leave it to default value if your ITsource is unmodified.  
Revision 5: a OR || was changed to a AND &&. That is all. Fixes the presence of encoded kito header  
Revision 6: Now able to give an array of random numbers instead like: 4,7,2,74,23,64 instead  
Revision 7: Raised line length limit from 255 to 25500  
Revision 8: Github version

## Usage
1. Select a input file,
   1. be it a .dat file you want to decrypt
   2. or a .txt file you want to encrypt
2. Select a output file
   1. be it a .dat file you want to decrypt
   2. or a .txt file you want to encrypt
3. Select ".dat file output" for encryption or deselect for decryption. This is selected for you automatically.
4. Input your xor key if your game uses a custom key. Remember to save it so you dont have to rewrite it every time.
5. DO IT button to do the thing.

Use "Swap input and output" to quickly change between encrypt and decrypt.

## Decrypt
![alt text](http://kito.staunhansen.dk/doc/IT%20XOR07/decrypt4.png "Example of decrypting dat files")

## Encrypt
![alt text](http://kito.staunhansen.dk/doc/IT%20XOR07/encrypt4.png "Example of encrypting dat files")
