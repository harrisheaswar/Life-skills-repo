# OSI Model
                                                 
## Definition: ##
OSI stand for Open System Interconnection Model. It primarily talks about how data is transferred from one computer to another. Computers with different manufacturers use OSI Model to communicate with each other. It is a seven layer model.

#### Application Layer #### 
Application layer is used by network applications like Firefox and Google Chrome. Any application that communicates over the network uses application layer. Some of the application protocols include http,https. For transfer of files we use ftp, While for web surfing we use http protocol. Emails use smtp and virtual terminals use telnet.

#### Presentation Layer #### 
It gets data from the above layer and converts it into binary format for machines to read. It compressess the data for faster data transmission. This layer is also responsible for encryption and decryption. It uses SSL(Secure Sockets Layer) Protocol to do the same.

#### Sessions Layer  ####
The sessions layer helps in setting, managing and termination of connections. Sessions use APIs like NETBIOS which helps apps communicate with each other. Before a session is established servers perform authorization and after that authentication. When downloading files, sessions layer keeps track of it. Sessions are created for each file and it tracks the data packet of the file.

#### Transport Layer ####
Transport layer controls the reliability of communication through segmentation. Data received from a session is divided into data units called segments. Each segment has a source and destination port number and a sequence number. Port numbers help direct each segment to correct application. Sequence numbers reassemble the segments to form the correct message sent to the receiver. Transport layer also controls the amount of data being transmitted. Finally, it helps in error control if data doesnt reach a destination. It uses Repeat Request Schemes to retransmit data.

#### Network Layer ####
Network layer works for the transmission of the data segments. It assigns sender and receiver IP address to each segment to form an IP packet. Ip address is assigned so that the packet reaches the right destination. 

#### Data Link Layer ####
It receives packets from the network layer. Data packets contain IP addresses of the sender and receiver. Physical addressing is done in this layer where Mac address of sender and receiver are assigned to each data packet to form a frame. Mac address is a 12 digit alphanumberic code embedded in the network interface card of a pc.

#### Physical Layer ####
This layer converts the binary sequence into signals and transmits it over local media. The signals can be electrical signal in case of copper wire, light signal in case of optical fibre or radio signal in case of air. At the receivers end, it receives the signal and converts it to binary data and passes it to Data Link Layer.

#### Conclusion #### 
All the seven layers work together to transfer data from one place to another.



#### Reference ###
***https://www.youtube.com/watch?v=vv4y_uOneC0***

***
Written By: Harrish Easwar






