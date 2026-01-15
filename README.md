1: for set this Auth System
npm install

for use signup 
 method post 
 http://localhost:4000/api/auth/signup
request body
 {
 
    "name":"demo",
    "email":"demo1@gmail.com",
    "password":"123456"

 }

  response body
{
    "message": "User already exists",
    "userData": {
        "_id": "6968c008f08e5c1401c394f2",
        "name": "Dipanshu Shukla",
        "email": "demo1@gmail.com",
        "password": "$2b$10$8y0zOGWABkuOq24uibtn2esuarbL7Sd7KhjHZ/TANfUrZtxRQMjJG",
        "createdAt": "2026-01-15T10:23:04.547Z",
        "updatedAt": "2026-01-15T10:23:04.547Z",
        "__v": 0
    }
}


 for use login api
 http://localhost:4000/api/auth/login

 request body
 {
    "email":"demo1@gmail.com",
    "password":"123456"
}

 response body

{
    "message": "Login successful",
    "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1c2VySWQiOiI2OTY4YzAwOGYwOGU1YzE0MDFjMzk0ZjIiLCJpYXQiOjE3Njg0NzQ2OTEsImV4cCI6MTc2ODU2MTA5MX0.HSgzwDHYWBdo9AP7joAGAONAKZqMMwl7F3EENw3k2hM"
}


  To get user by id
  http://localhost:4000/api/users/65ab1234567890abcdef123
  

 
 
