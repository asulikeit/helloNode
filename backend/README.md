# Reference
- https://github.com/bjpublic/MEVN

# MONGODB
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

# NODEJS
    $ npm init
    $ npm i cors express mongoose morgan os-utils request socket.io

# Test file
- https://jsonplaceholder.typicode.com/comments

# How To
    $ npm start
