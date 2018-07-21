Implemented a protocol similar to Transmission Control Protocol on top of User Datagram Protocol using modular approach with C++
Flow control was managed using Go Back N Automatic Repeat Request and slow start with fast recovery scheme was used for congestion control of packets 
To run the code, do make this will create two executable files uclient and userver.
Run the two executable files in different places (same/different pc's) and transfer the data from one place to another