# MalwareDetection
<br/>


  <h3 align="center">MalwareDetection</h3>



## Table Of Contents

* [About the Project](#about-the-project)
* [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [Github Versioning](#github-versioning)
* [Unittesting](#unit-test)
* [BuildTool](#Build-tool)
* [Jenkins](#jenkins)
* [Selenium](#selenium)



## About The Project

![Screen Shot](/static/img/screenshot.png)

In today’s world, everything is dependent on the internet in some way or another. The growing cyber world has brought a lot of new inventions and made our life easier than ever. The year 2020 has shut down all the offline markets, thus the user base of all the online applications has grown rapidly. From a kindergarten-going child to a B.Tech student, everyone is on the internet to attend their education, offices have moved to Work from Home culture. As a result, the risk of cybercrimes and hacking has increased and internet users are now more prone to be the victims of these attacks.


Malware is a piece of software, that is installed on the victim’s computer, which harms the systems and collects important data. Malware is of many types such as Viruses, worms, ransomware, adware, spyware, and trojan horse.

This Project helps in detection of malware in a .exe File


## Built With
This app is built in Flask

## Getting Started


### Prerequisites

This is an example of how to list things you need to use the software and how to install them.

* FLask

```sh
pip install Flask
```
* Docker

```sh
https://docs.docker.com/desktop/
```

### Installation

1. Install Flask

2. Clone the repo

```sh
git clone https://github.com/Rajat-Kaushik/MalwareDetection.git
```

3. Install requirements.txt

```sh
pip install -r requirements.txt
```

4. Run Docker compose up
```sh
docker-compose up
```
5. Go to the following link to go to app.

```sh
http://localhost:5000/
```


### Github Versioning

1. Making tags in the github
```sh
git tag <tagname> <commit id>
git push --tags
```

2. Make a release using github using these tags
3. Checkout tag 
```sh
git checkout <tag name>
```


### Unit test

1. Running locally 
→ Go to Desktop/tool folder. Open terminal. 
Run
```sh
pyb -v
```

2. Running Through jenkins
Will send mail to all members if any of the test case fails


3. Running locally and generating html report
→ Go to Desktop/test folder. run the following command. It will generate the report name as   report.html in the test folder.

```sh
pytest -v -s --html=report.html --self-contained-html
```

### Buildtool

Using pybuilder as build tool. The demonstration is done above (using pyb)


### Jenkins
1. Open the dashboard
2. It will have the malware detection job configured to send mail to all the members on wrong commit
3. On every commit it will run the build in 1 minute. If the build fails, it will send the mail to all the members

### Selenium
Inside malwaredetection/selenium folder, open terminal. then run the following two commands one by one.
```sh
python Selenium.py

python Selenium1.py
```


