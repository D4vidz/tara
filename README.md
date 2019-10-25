# Tara
Use Go build RESTful API to call

## Prerequisite
1. [Gin Web Framework](https://gin-gonic.com/docs/quickstart/)
2. [GORM](https://gorm.io/docs/index.html)

## API Examples
### run server locally
```
go run main.go
```
### hello world!
```bash
curl -XGET http://localhost:8080/
```
### Users API
> Use Postman temporarily
```
# create user
curl -X POST localhost:8080/api/v1/users/

# get all users
curl -X GET localhost:8080/api/v1/users/

# get single user
curl -X GET localhost:8080/api/v1/users/1

# update user
curl -X POST localhost:8080/api/v1/users/1

# delete user
curl -XDELETE localhost:8080/api/v1/users/1
```