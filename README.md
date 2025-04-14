# beanies
Beanie: Asynchronous Python object-document mapper [ODM] for mongodb based on Motor and Pydantic
what is ODM - a tool interacts with document databases like mongodb by mapping application objects to documents in the database


what is Postman: API platform used for building, testing, designing, modifying and documenting APIs 
used to test the APIs
Developers may quickly create, test, share, and document APIs with teh help of this tool.
It enables control of every phase of the API lifecycle.

Collection: It is a group of API Requests

200 - OK
201 - Created
202 - Accepted
203 - Non-authoritative information
204 - No content
205 - Reset content
206 - Partial Content


HTTP WebSockets differences
HTTP:
Unidirectional
Stateless   [because each request is independent — the server does not remember anything about previous requests from the same client]
half duplex [ data flows in one direction at a time (either send or receive) ]

Websocket : 
stateful [every request and response is dependent like online games & chatting ]
Bidirectional
Full duplex [client & server side receive & send the data at a time]

short polling in websocketserver:
The client sends HTTP requests to the server at regular intervals (e.g., every few seconds) to check for updates.The server responds immediately, regardless of whether new data is available.
Long polling in websocket server:
The client sends a request to the server, which holds the connection open until new data is available or a timeout occurs. Once the server responds, the client immediately sends a new request, repeating the process.
Reduces unnecessary requests compared to short polling.
