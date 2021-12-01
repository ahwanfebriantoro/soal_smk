# Quiz Node.js .

In this quiz i need you to make 2 endpoint. and database called user. that received user data. it contains:
- Username
- Password

and have validation:
- username must be unique

```
/register => to register a new user with hashing password

expected response:
{
"message": "User is Successfully Created"
}

if user is registered already response"
{
"message": "User Already Created"
}

```
```
/login => search user by their username and compare the user password and incoming password

fail expected response:
{
"message": "Wrong password"
}

expected response:
{
"message": "Legitimate User"
}
```
