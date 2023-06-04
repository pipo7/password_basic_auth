# password_basic_auth

Run the program 
go run main.go &

Test using POSTMAN

POST request 
http://10.145.70.97:8000/signup 
with body {"username":"user2","password":"password2best"}

it shows console output :
key is : user2 and value is : $2a$07$yRyjumWLPG6spxhdEvr7/e0e26p92oYHNHQyVbj7/.2Jyz53kxcoG/

POST request
http://10.145.70.97:8000/signin with body {"username":"user2","password":"password2best"}
response: Welcome user2!