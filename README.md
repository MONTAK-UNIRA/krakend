-- COMMAND
-- Run the following command to install the required packages:
```bash
docker run -p 8080:8080 -v "${PWD}:/etc/krakend/" devopsfaith/krakend:watch run -d -c /etc/krakend/krakend.json

```

- COMMAND IF MONGO DB IS NOT ACTIVE

```bash
sudo mongod --fork --logpath /var/lib/mongodb/mongodb.log --dbpath /var/lib/mongodb
```