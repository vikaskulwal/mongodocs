# MongoDB Setup

## Install Mongo DB server on Windows
https://docs.mongodb.com/manual/tutorial/install-mongodb-on-windows/

## Enable Security and create users
https://medium.com/@matteocontrini/how-to-setup-auth-in-mongodb-3-0-properly-86b60aeef7e8

## Commands:
use admin

### Create a new admin user
db.createUser({ user: "admin", pwd: "svhostel", roles: [{ role: "userAdminAnyDatabase", db: "admin" }] })



