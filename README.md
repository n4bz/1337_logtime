# 1337_logtime

## How to install
First, you need to install the packages needed

```
pip3 install -r requirements.txt
```

You will also need to update the config file with your **client_id** and **client_secret** in config.conf 
```
42.client_id = YOUR_CLIENT_ID
42.client_secret = YOUR_CLIENT_SECRET
42.token_url = https://api.intra.42.fr/oauth/token
42.endpoint = https://api.intra.42.fr
42.login = YOUR_LOGIN
```

## How to use
You can execute the script from the folder like this :
```
python3.7 logtime.py
```
Or you can add an alias in your .bashrc or .zshrc like this :
```
logtime='(cd ~/1337_logtime && exec python3.7 ~/1337_logtime/logtime.py)'
````
This way you will be able to execute the script from anywhere in your terminal.
