# Simple-REST-Interface-Test
Coding Homework Assignment
Its query the "https://macaddress.io" MAC address lookup API

curl -i -H "Accept: application/json" -H "Content-Type: application/json" https://api.macaddress.io/v1?apiKey=YOUR_API_KEY&output=json&search=43:38:39:ff:ef:21

-------------------

Below command For "dockerized" bash script  

docket build -t anurajvijayan/macadress.sh https://github.com/anurajvijayan/macadress.git

--------------------

Below command For "RUN" the docker

docker run -p 8000:8000 -d anurajvijayan/macadress

+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

Test
----
You can Test these scripts on any OS that supports BASH.

First, clone the GIT repository using command:

$ git clone https://github.com/anurajvijayan/[name]
Go to the cloned directory:

$ cd [name]/
Git checkout to the latest stable release:

$ git checkout v1.22.0
Finally, Test the Bash-Snippets using command:

$ sudo ./macadress.sh


