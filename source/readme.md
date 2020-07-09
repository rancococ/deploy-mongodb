
## Mongo And Mongo Express

### Mongo
```
port:27017
environment
      - MONGO_INITDB_ROOT_USERNAME=admin
      - MONGO_INITDB_ROOT_PASSWORD=admin123
```


### Mongo Express
```
port:8081
environment
      - ME_CONFIG_OPTIONS_EDITORTHEME=ambiance
      - ME_CONFIG_MONGODB_SERVER=127.0.0.1
      - ME_CONFIG_MONGODB_PORT=27017
      - ME_CONFIG_BASICAUTH_USERNAME=mongo
      - ME_CONFIG_BASICAUTH_PASSWORD=mongo123
      - ME_CONFIG_MONGODB_ENABLE_ADMIN=true
      - ME_CONFIG_MONGODB_ADMINUSERNAME=admin
      - ME_CONFIG_MONGODB_ADMINPASSWORD=admin123
```
