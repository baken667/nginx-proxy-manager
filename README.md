# This is nginx proxy-manager sample


## Generate secrets
```bash
openssl rand -hex 32 > .secrets/db_root_pwd.txt && openssl rand -hex 32 > .secrets/mysql_pwd.txt
```