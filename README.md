# PyMail
#### A simple Python GUI based SMTP and POP3 Client 
----------------------------------------------------------

## Setup  
- Clone the repo:
```shell
git clone https://github.com/anshulshah96/PyMail.git
```
- Create a Local File in the folder with name conf.py and add:
```python 
USERNAME = "your username"
PASSWORD = "your password"
HOST_ADDR = "192.168.180.11" # IITR SMTP AND POP3 ADDRESSS
POP3_PORT = 110
SMTP_PORT = 587
MESSAGE_LIMIT = 20
```
- Start the GUI User Agent:
```shell
python guitest.py
```

## License
[MIT License](http://anshul.mit-license.org/)
