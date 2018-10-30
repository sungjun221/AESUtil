AESUtil
=============
 
This project is an example of encryption / decryption using AES algorithm in JAVA.
To exchange data using the AES algorithm, the following must be defined.
 
## AES algorithm specification example
* Key size: 256 bits
* Encryption mode: CBC
* Padding method: PKCS5
* Encryption key: 12345678901234567890123456789012 (32 characters)
	* Initialization vector (in CBC mode): 1234567890123456 (16 characters)
* Key / passphrase encoding method: Base64 (byte encoding) + UTF-8 (character encoding)
 
## Encoding
If you need to extract the key, you need to define the encoding method.
In the example, the byte encoding was Base64 and the character encoding was UTF-8.


* * *

AESUtil
=============
 
이 프로젝트는 JAVA에서 AES알고리즘을 사용하여 암복호화하는 예제이다.
AES알고리즘을 이용하여 데이터를 교환하려면 아래의 내용을 정의해야 한다.
 
## AES알고리즘 스펙 예
* Key size : 256 bit
* 암호화 모드 : CBC
* Padding 방식 : PKCS5
* 암호화키 : 12345678901234567890123456789012 (32자)
* 초기화벡터(CBC모드일 경우) : 1234567890123456 (16자)
* 키/암호문 인코딩 방식 : Base64(바이트인코딩) + UTF-8(문자인코딩)
 
## 인코딩
Key를 추출해야 할 경우 인코딩 방식을 정의해야 한다.
예제에서는 바이트인코딩은 Base64, 문자인코딩은 UTF-8으로 하였다.