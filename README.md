# Fiber version of PPT
This is a dockerized service for PTT.
The code was originally stollen from Fiber Examples.

I will be replacing the DB with a BOLTdb Embedded DB.
It will respond to update commands for the BOLT system.  Possibly a PubSub kind of solution but not sweating it.

Will be introducing a ProtocalBuffers/gRPC solution specifically for compiled Swift, Kotlin and Flutter apps, but also REST.

WIll build a COBRA CLI to interface with the service, but using gRPC/PROTOBUFFS.

MORE TO COME.







GET /api - Say hello
POST /auth/login - Login user
GET /user/:id - Get user
POST /user - Create user
PATCH /user/:id - Update user
DELETE /user/:id - Delete user
GET /product - Get all products
GET /product/:id - Get product
POST /product - Create product
DELETE /product/:id - Delete product



TODO:

1. Add EmbeddedDB
    - BoltDB
    - 
2. TESTIFY 

3. DOCKERIZE

