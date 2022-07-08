## Jjtech GCP CICD Runbook

### SonarQube Credentiala

```
Token: gcp_cicd_project: bd4d34ba108ef50890e034d04eb86b597b9728fc
```

```
mvn sonar:sonar \
  -Dsonar.host.url=http://34.125.37.18:9000 \
  -Dsonar.login=bd4d34ba108ef50890e034d04eb86b597b9728fc
  ```
  ```
  username:admin
  pwd:admin
  ```

  ### Nexus Credentials
```
username:admin
pwd:admin
IP:34.125.184.227
mvn -emp admin ====> use this command to obtain Nexus encrypted password
Nexus Master Encrypted Password:RxUM2hruJSkHaD/7OfXzfr1kaibBGJfXwEtk6YE+gzs=
mvn -ep admin =====> use this command to obtain nexus normal password
Nexus Normal Encrypted Password:MawEKu5Qy4EHmnCdtILDHHCCGEiDHIt3G8SGmrc6NO8=
```


### Maven Credentials
```
username:admin
pwd:admin
IP:34.125.191.179
```


### Ansible Credentials
```
username:ansible
pwd:ansible
IP:34.125.191.179
```


### Jenkins Credentials
```
username:admin
pwd:admin
IP:34.125.120.231
```


### Github Credentials
```
webhook:http://34.125.108.84:8080/github-webhook/
```