**Created with love for openMag journal. you can run `check-encrypt` to see what can you do with it!**  
just use it to make sure your file(s) are safe...  
> it's the usage function in script: 
	
	This script used for encrypting or decrypting files with gpg automatically!
	check-encrypt [options]

	-a : understand as ALL means all files in that directory!(it's just a while loop)
	-p : used to decrypt or encrypt files with a speciall password
	-f : used to set a file that you want to encrypt or decrypt it
	-r : remove the files after you used them to decrypt or encrypt
	-h : print this help message
	
	example guide :
       	check-encrypt -p 'password' -f path/to/file -r
	check-encrypt -p 'password' -a -r 
	check-encrypt -p 'password' -a
	check-encrypt -f path/to/file -r 
 	check-encrypt -f path/to/file
	check-encrypt -a -r
	check-encrypt -a

