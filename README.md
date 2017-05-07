# rabbit_ransomware

Derived from AwesomeWare (php ransomware v2) from Bug7sec Team https://github.com/bug7sec/Ransomware

Deface index template from Kerala Cyber Warriors

Steps:
1) Upload rabbit.php to the server, open it from browser, enter encryption key and select infect option.
2) Now open the website home (or any random page) and you will land at the decryptor index page. Enter  the key to decrypt files.


The encryption key should contain a substring 'r4b1t' (This is specified in base64 decoded code in line 49 of rabbit.php). This is to check for false key entries for decryption.
