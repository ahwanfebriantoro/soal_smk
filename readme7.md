# Quiz Node.js .

In this quiz i need you to make 2 endpoint. and database called user. that received user data. it contains:
- Username = string
- Password = string
- fullname = string
- age = number
- occupation = string
- isMarried = boolean


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


```
/findByAge => search user by their age that greater than the input
```


```
/findByOccupationAndAge => search user by their age greater than the input and by their occupation
```

```
/findName => search user by their name though i will input it from middle front or back
```
