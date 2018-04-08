# DEX 

PROJECT WHIT HTTPS 

# HTTPS - Certificado

## INSTALAR OPENSSL

[WIN32 OPENSSL] (https://slproweb.com/products/Win32OpenSSL.html)

## GENERAR CERTIFICADO

[SSH_TEST_CERTIFICATE] (https://www.akadia.com/services/ssh_test_certificate.html)
 
```
openssl req -new -newkey rsa:2048 -nodes -keyout server.key -out server.csr
```

```
openssl x509 -req -days 365 -in server.csr -signkey server.key -out server.crt 
```

[x509 values mismatch] (https://stackoverflow.com/questions/26191463/ssl-error0b080074x509-certificate-routinesx509-check-private-keykey-values)