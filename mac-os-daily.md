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
```
