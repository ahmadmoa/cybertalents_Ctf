   
# cyberustask1
	who am i 
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


# cyberustask2
# Admin has the power
After I navigate to the link I try to view page source so, I find this credentials : (user:support password:x34245323) I try to login with it but I find that I need to increase my privilage then I change the cookie from role:support to role:admin , then I find the flag


# I am legand
I try to view page source so I find jsfuck encoding strings then I try to decode it by this site: https://filipemgs.github.io/poisonjs/ then I find the flag

# Crack the Hash
I try this site: https://md5.gromweb.com/?md5=1ab566b9fa5c0297295743e7c2a6ec27 to decrypt the hash then I find the flag

# Guess the password
 Simply try this site: https://hashes.com/en/decrypt/hash to find the flag

# Business Gathering
 First I read the given information carfeully l, then I tried to search google for " huge cyber security conference ". I found a website which lists 8 of cyber security confrences with their details https://www.techtarget.com/whatis/feature/8-cybersecurity-conferences-to-attend I seached with the location and I found San Francisco in the second conference. finally I took its name and it worked.

# Hidden Message
 After visiting the link it opens to a page containing only one single image, after trying to inspect the page I found nothing helpful. So, I downloaded the image then opened it with exiftool to see its information. I found something weird in the the Copyright Notice, I took it to hash analyzer https://www.tunnelsup.com/hash-analyzer/ and it said that it was MD5, exactly as cyber talents said. I submitted it, and it works.