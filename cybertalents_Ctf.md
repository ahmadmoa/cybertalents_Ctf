   

# who am i 
 - At the beginning we tried to view the page source. We found a comment that directed us that for a guest account use: Guest Guest We tried to login with these credentials, But we found a message that says access denied you need administrator privileges. So we looked in the cookies, we found it encoded to base64 so we decoded it and we found it was "login=Guest". We changed it "login=admin" then encoded it to base64. After that we used burp to intercept the request to edit the cookies to what we have changed. It worked out.
   
   # easy access
    
    after i navigate to the given link i find login page then i try to write single quote in the two fields then i find this error " Error: You have an error in your SQL syntax; check the manual that corresponds to your MariaDB server version for the right syntax to use near 'e2f43259cb63e38b9ed8d2d24af245e9'' at line 1" so , i try to write a full payload admin' '1'='1''-- then i logged as admin i get the flag flag{!njection_3v3ry_wh3r3}

# keep it simple
at the start of the challenge we viewed the source of the page we found that there was 3 images: the_eye.jepg img/the_eye.jepg Hint.jepg we used exiftool to see the meta data after downloading the images from the website where we found the flag

# Louder
Download the attached audio then upload it to this site [https://morsecode.world/international/decoder/audio-decoder-adaptive.html](https://morsecode.world/international/decoder/audio-decoder-adaptive.html "https://morsecode.world/international/decoder/audio-decoder-adaptive.html") you will get the flag :
flag{I am speaking louder than before}

# Hide Data
 
We took the data and put it on a website: [https://www.dcode.fr/caesar-cipher](https://www.dcode.fr/caesar-cipher "https://www.dcode.fr/caesar-cipher") to decode it. After decoding it appears to be " the flag is 2j68yfhqlz It is pretty easy to see the flag but can you see it i took nearly 1 minute to encode this with ROT13 good luck in solving that ". Then we have put "2j68yfhqlz" as the flag and it worked out.
