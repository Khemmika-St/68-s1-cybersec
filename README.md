# Cyber Security 

## Information  
- Khemmika Suttichat (KHEM) 
- 6602041620041 
- s6602041620041@email.kmutnb.ac.th
## Environment 
``` sh
cp env.simple .env
``` 

## Running a services
###Database
``` sh
docker compost -f db.yaml up # monitoring
docker compost -f db.yaml up -d #backaround
```
###Admin
``` sh
docker compost -f admin.yaml up # monitoring
docker compost -f admin.yaml up -d #backaround
```