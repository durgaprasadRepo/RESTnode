RESTful Services with nodejs


Methods supported  GET , POST , DELETE

how to run

Terminal 1

$ node nodeREST.js


Terminal 2 

//POST

$ curl -d 'gatorade' http://127.0.0.1:8000

//GET

$ curl http://127.0.0.1:8000

//DELETE

$ curl  -X 'DELETE' http://127.0.0.1:8000/1


PS: install curl 

sudo apt-get update

sudo apt-get install curl
