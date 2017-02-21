# certificateReader

Checks with kind of file is the cert (binary or not) and try to open it, using openssl, with differents encoders/structures.

```
./certificateReader.sh file.cer
```


Verify cert with a CA:
```
python certificate_verify.py -c miserver.pem -a ca.der -a ca_int.pem
```

Needs pyOpenSSL and python3
