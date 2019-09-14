# node-https
Test simple https request on nodejs.

To enable https request on express server, execute the commands below:


`openssl genrsa 1024 > key.pem`

`openssl req -x509 -new -key key.pem > key-cert.pem`

And finally:  
`node server.js`

Now, you can use https://localhost:8001
