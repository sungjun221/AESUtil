AESUtil
=============
 
This project is an example of encryption / decryption using AES algorithm in JAVA.
To exchange data using the AES algorithm, the following must be defined.
 
## AES Algorithm Specification Example
* Key size: 256 bits
* Encryption mode: CBC
* Padding method: PKCS5
* Encryption key: 12345678901234567890123456789012 (32 characters)
	* Initialization vector (in CBC mode): 1234567890123456 (16 characters)
* Key / passphrase encoding method: Base64 (byte encoding) + UTF-8 (character encoding)
 
## Encoding
If you need to extract the key, you need to define the encoding method.
In the example, the byte encoding was Base64 and the character encoding was UTF-8.