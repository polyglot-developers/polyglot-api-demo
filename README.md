# Polyglot API Demo #

![alt text](polyglot-image.png)

## RESTful API Implemented in Multiple Languages ##
* Go 
* Node.js (Express)
* Python (Flask)
* Java (Spring Boot)


# API Endpoints #

* curl http://localhost:PORT

```
{
    "message": "Hello Node.js"
}
```

* curl http://localhost:PORT/users
```
[
    {
        "username": "bchan",
        "firstName": "Brian",
        "lastName": "Chan"
    },
    {
        "username": "rfederer",
        "firstName": "Roger",
        "lastName": "Federer"
    }
]
```

* curl http://localhost:PORT/users/bchan

```
{
    "username": "bchan",
    "firstName": "Brian",
    "lastName": "Chan"
}
```
