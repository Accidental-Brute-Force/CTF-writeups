## Fortunately we have a quarantine file for you!

### Description
### Solution
Find the right [script](https://github.com/herrcore/punbup) to open/extract `.bup` files. A hint could be found on the website of the challenge creator (Didier Stevens).

You'll find 2 files: Details and File_0. If you run the `file` command you will find that File_0 is a zip file. The zip file is password protected. Try the Details file for info.

When successfully extracted with the password `Win32/BackDoor-ZIPPW.g` which could be found in the Details file. `cat` the extracted virus.exe file to find the flag.
``` 
$ cat virus.exe 
This is a very dangerous virus!!!
   
:-)
   
CSC{15wtuNdW2ScSxbBiAHIP}
```

### Flag
`CSC{15wtuNdW2ScSxbBiAHIP}`
