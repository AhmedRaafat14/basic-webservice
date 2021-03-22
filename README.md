# basic-webservice
This is a very basic web-service created to learn about GO

* Clone the repo:
```bash
$ git clone https://github.com/AhmedRaafat14/basic-webservice.git

$ cd basic-webservice/
```

* Build and bring the web-service up:
```bash
$ go build .
$ ./webservice
```

* API requests:
```
GET http://localhost:3000/users // Return all users

GET http://localhost:3000/users/1  // Return specific user by ID

POST http://localhost:3000/users   // With body to create new user
{"FirstName": "Ahmad", "LastName": "Raafat"}

PUT http://localhost:3000/users/2   // With body to update an existing user
{"ID": 2, "FirstName": "Ahmaad", "LastName": "Raafat"}

DELETE http://localhost:3000/users/1  // Delete specific user by ID
```