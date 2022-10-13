# Run Apache NiFi in Docker with SSL Enabled

1- Download Apache NiFi Toolkit Binary 1.17.0 [from here](https://dlcdn.apache.org/nifi/1.17.0/nifi-toolkit-1.17.0-bin.zip) if the link did not work go to [this page](https://nifi.apache.org/download.html) and find the working download links
<br>2- Extract it with the following command:
```console
vahid@Vahid-HP:~$ unzip nifi-toolkit-1.17.0-bin.zip 
vahid@Vahid-HP:~$ cd ./nifi-toolkit-1.17.0/bin
vahid@Vahid-HP:~$ ./tls-toolkit.sh standalone -n 0.0.0.0 -C 'CN=admin,OU=NiFi' --subjectAlternativeNames '0.0.0.0'
```
<br>3- 
