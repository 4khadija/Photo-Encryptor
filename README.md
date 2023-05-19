# Ransomware-Photo-Encryptor-Demo
Ransomware is a type of malware from cryptovirology that threatens to
publish the victim's personal data or permanently block access to it
unless a ransom is paid off.
<p> In this project I have demonstrated how ransomware is used to encrypt user’s images
from ‘Pictures’ folder and demands ransom to decrypt them. 
  <br>
  
The BlowfishPhotoEncryptor is a Java program designed to encrypt photos
using the Blowfish encryption.
</p>

# The program operates as follows:
- It begins by specifying the secret key and encryption algorithm to
be used.
- The program identifies the user's home directory using the
"user.home" system property.
- It locates the "Pictures" folder within the user's home directory.
- After a wait of 5 secs the program encrypts all image files (with
extensions .png, .jpg, .jpeg, .bmp, and .gif) found in the
"Pictures" folder and its subdirectories. It recursively encrypts
files in subdirectories.
- After encryption, the original image files are deleted.
- The program creates a folder named "DecryptedPhotos" on the
user's desktop.
- It selects one encrypted photo from the "Pictures" folder and
decrypts it.
- The decrypted photo is saved in the "DecryptedPhotos" folder
with the ".enc" extension removed.
- A GUI window is displayed, showing a message to inform the
user that the photos have been encrypted and they must pay
ransom amount to decrypt all their photos. It also displays an
image and plays a sound clip to attract the user's attention.
# Compilation and Execution
When the user tries to run the compiled Java file
(BlowfishPhotoEncryptor.java) using: ‘Java BlowfishPhotoEncryptor’:-
<br>

after 5 sec the images in the pictures folder will be encrypted and the
user will not be able to open them. The user will see the prompt of
warning demanding ransom in exchange of decrypting images.
<br>
