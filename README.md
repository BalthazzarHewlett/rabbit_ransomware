# rabbit_ransomware

Derived from AwesomeWare (php ransomware v2) from Bug7sec Team https://github.com/bug7sec/Ransomware

Deface index template from Kerala Cyber Warriors

Steps:
1) Upload rabbit.php to the server, open it from browser, enter encryption key and select infect option.
2) Now upload the deface index (index.php). The site admin can now visit the site and decrypt the files by entering the key there.


The encryption key should contain a substring as specified in line 358 of index.php. This is to check for false key entries for decryption.
