# OpenLDAP
Docker compose file for OpenLDAP and phpLDAPadmin deployment with data persistance, meant for local development and testing environment with LDAP connection and authentication.

### OpenLDAP

##### Ports:
```bash
- "389:389"
- "636:636"
```

##### Setup:
```bash
docker-compose up -d
```


### phpLDAPadmin

##### Ports:
```bash
- "80:80"
```

##### Login:
```bash
DN: cn=admin,dc=localdomain,dc=com
Password: secret
```
