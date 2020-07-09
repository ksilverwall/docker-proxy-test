Docker Reverce Proxy Test
---

## Setup Host

```
127.0.0.1 proxy-test.docker
```

## Create Cert

```
mkcert -cert-file ./certs/localhost.crt -key-file ./certs/localhost.key localhost
mkcert -cert-file ./certs/proxy-test.docker.crt -key-file ./certs/proxy-test.docker.key proxy-test.docker
```
