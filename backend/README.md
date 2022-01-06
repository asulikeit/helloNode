# Backend server

## MONGODB
    use log
    db.log.insert({"temp": 0})
    show dbs
    db.createUser({
        user: "dabin",
        pwd: "dabin12010",
        roles: [
            {
                role: "readWrite",
                db: "log"
            }
        ],
        mechanisms: [
            "SCRAM-SHA-1"
        ]
    })
    db.getUsers()

## NODEJS
    $ npm init
    $ npm i cors express mongoose morgan os-utils request socket.io

## Test file
- https://jsonplaceholder.typicode.com/comments

## How To
    $ npm start
