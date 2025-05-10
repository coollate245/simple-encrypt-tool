# simple-encrypt-tool
This is a simple encrypt tool that i make in free time
ps: there will be plenty update in the future
# installation
```bash
git clone https://github.com/coollate245/simple-encrypt-tool
cd simple_encrypt_tool
chmod +x encrypt.py
```
# how-to-use
usage: encrypt.py [-h] [-e ][-de ] [-n ] [-k ]

simple hashing tool
```
options:
  -h, --help          show this help message and exit
  -e  , --encrypt     encrypt mode(file/folder)
  -de  , --decrypt    encrypt mode(file/folder)
  -n  , --name        input data name
  -k  , --key         Decryption key (from key file or manual input)
```
# exemple
file encrypt/decrypt
```
py encrypt.py -e file -n [yourfilename]
py encrypt.py -de file -n [yourfilename] -k [yourkey]
```

folder encrypt/decrypt
```
py encrypt.py -e folder -n [yourfilename]
py encrypt.py -de folder -n [yourfilename] -k [yourkey]
```
