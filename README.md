# ead-api

### MONGO

- acessar container: `docker exec -it 2d06a6b1a348 /bin/bash`
- acessar mongo: `mongo -u root -p`
- criar banco de dados: `use eadapi`
- listar bancos de dados: `show databases`
- criar user: `db.createUser({user: "ead_api_user", pwd: "ead_api_user", roles: ["readWrite"]})`
- listar users: `show users`
