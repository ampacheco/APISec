# APISec

# Active API Reconnaissance

## Using nmap Tool
```
# First Command
nmap -sC -sV 127.0.0.1 #

# 
nmap -p- 127.0.0.1 #

#
nmap -sV 127.0.0.1 -p 8025
```

## Using amass Tool

````
#
amass enum list #

#
amass enun -active -d crapi.apisec.ai #

# example of output, usin Microsoft.com

amass enun -active -d microsoft.com #
![image](https://github.com/user-attachments/assets/0532ed8e-5a9b-400b-a54d-c457cdf06957)


# Example
amass enum -active -d microsoft.com |grep api
````
## Using gobuster
```
sudo apt-get install gobuster -y  # Install GoBuster
```
