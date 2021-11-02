# SSH

## Type of files
1. Private Key
   1. It has no extention usually
   2. It has **BEGIN PRIVATE KEY** written inside
2. Public Key
   1. It has extention **.pub** usually

## How to access
```bash
# ssh -i ~/.ssh/private_key -p <port> username@ip_address
ssh -i ~/.ssh/id_rsa -p 22 username@10.10.10.10
```
