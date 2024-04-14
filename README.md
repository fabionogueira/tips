# tips

## pfx to pem
``` bash
openssl pkcs12 -in myfile.pfx -out myfile.pem -legacy
```

## kill by port
``` bash
netstat -tulpn | grep :8000
kill -s 9 55476
```
