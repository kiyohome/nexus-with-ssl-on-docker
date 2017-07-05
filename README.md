# nexus-with-ssl-on-docker

## Tools

- [Nexus](http://www.sonatype.org/nexus/)
- With
  - [How to Enable the HTTPS Connector](https://books.sonatype.com/nexus-book/reference3/security.html#ssl-inbound)

## How to build image

- clone the repository

```
  $ git clone https://github.com/kiyohome/nexus-with-ssl-on-docker.git
```

- build the image

- no proxy

```
  $ cd 3.3.2/
  $ docker build -t kiyohome/nexus-with-ssl-on-docker:3.3.2 .
```
