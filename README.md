# README

## How to Run
- install Ruby (atleast v2.0)
- install Rails (v5 or latest)
- run command below
```
$ bundle install
$ rails db:migrade
$ rails server
```
- the application will be run on port 3000

## Post
### /users
```json
body: {
    "username": username,
    "name": name,
    "password": password,
    "password_confirmation": password,
    "email": email,
}
```
### /auth/login
request:
``` json
body: {
    "email": email,
    "password": password,
}
```
## Get
### /users/
``` json
header: {
    "Authorization": _token_
}
```
