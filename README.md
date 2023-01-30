# registration
post

POST
url : https://blog.kata.academy/api/users
запрос : 
{
    "user": {
        "username" : "MotorovIlia",
        "email": "ilamotorov@gmail.com",
        "password" : "123456"
    }
}
ответ: {
    "user": {
        "username": "motorovilia",
        "email": "ilamotorov@gmail.com",
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjYzZDc4YzI4NmY4YmVlMWIwMDU1MTgyMCIsInVzZXJuYW1lIjoibW90b3JvdmlsaWEiLCJleHAiOjE2ODAyNTQ1MDQsImlhdCI6MTY3NTA3MDUwNH0.X_gZGvCummwY8LfzUYHI1lYsajNu0UGrAhNrRrPyXJw"
    }
}

POST login:
url: url : https://blog.kata.academy/api/users/login
запрос : 
{
    "user": {
        "email" : "ilamotorov@gmail.com",
        "password": "123456"
    }
}
ответ : 
{
    "user": {
        "username": "motorovilia",
        "email": "ilamotorov@gmail.com",
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjYzZDc4YzI4NmY4YmVlMWIwMDU1MTgyMCIsInVzZXJuYW1lIjoibW90b3JvdmlsaWEiLCJleHAiOjE2ODAyNTQ1NjEsImlhdCI6MTY3NTA3MDU2MX0.3UlzrXjhZv6wCmi4B8Ri2vlPol_hevbNJYB3S_uCgs4"
    }
}

autorization:
url: https://blog.kata.academy/api/user
запрос пустой, только токен
ответ:
{
    "user": {
        "username": "motorovilya",
        "email": "ilymotorov@gmail.com",
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjYzZDc4NWE1NmY4YmVlMWIwMDU1MTgxYyIsInVzZXJuYW1lIjoibW90b3JvdmlseWEiLCJleHAiOjE2ODAyNTM0NjcsImlhdCI6MTY3NTA2OTQ2N30.9w5eU-j6957Ef1oH2769RXIYk1VhTydDoteqvnA9HZ4"
    }
}
