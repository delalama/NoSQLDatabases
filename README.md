# NoSQLDatabases
Testing NOSQL with SpringBoot, i've choosen MongoDB.

Install MongoDB on Ubuntu
---
You can choose between enterprise or community , i installed the community edition.
Enterprise Edition
---

enter in terminal

* sudo apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv 9DA31620334BD75D9DCB49F368818C72E52529D4

for Ubuntu 16.04...
* echo "deb [ arch=amd64,arm64,ppc64el,s390x ] http://repo.mongodb.com/apt/ubuntu xenial/mongodb-enterprise/4.0 multiverse" | sudo tee /etc/apt/sources.list.d/mongodb-enterprise.list

* sudo apt-get update

* sudo apt-get install -y mongodb-enterprise


Community Edition
---

Community edition :(https://hevodata.com/blog/install-mongodb-on-ubuntu/)

To begin with MongoDB basic commands we've this helpful web.

https://dzone.com/articles/top-10-most-common-commands-for-beginners

To make an easy SpringBoot application you can follow this simple Baeldung project

[baeldung]:https://spring.io/guides/gs/accessing-data-mongodb/
