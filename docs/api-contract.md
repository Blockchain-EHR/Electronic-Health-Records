\# API Contract



\## Auth



POST /api/auth/login



Request:

{

&#x20; "email": "doctor@test.com",

&#x20; "password": "123456"

}



Response:

{

&#x20; "token": "jwt-token",

&#x20; "role": "DOCTOR"

}

