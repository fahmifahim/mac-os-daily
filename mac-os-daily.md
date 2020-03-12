## Password Protect Zip Files in Mac OS X
```bash
$ zip -e [archive] [file]
$ zip -er [archive] [directory]

Sample command: 
$ zip -er archive.zip /path/to/directory/
Enter password:
Verify password:
adding: ~/Documents/Confidential/ (deflated 13%)

```

## Opening the Password Protected Zip
```bash
$ unzip filename.zip
# Note: if you open this .zip file on Windows, there will be error encoding on the File name. This is due to the UTF-8 and ShiftJIS difference between Mac-OS and Windows
```
