# nsp-chat
This is a simple chat demo by using Node.js, Socket.IO and protobuf.js.
#Hint
When use the protobuf.js,I meet some problem.Such as:  
```JavaScript
message AwesomeMessage {
    string awesome_field = 1; // becomes awesomeField
}
```

the field `awesome_field` will becomes `awesomeField`.

