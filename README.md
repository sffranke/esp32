# esp32 cam with esp32 range extenter  
https://github.com/martin-ger/esp32_nat_router  

portmap add TCP 8080 192.168.4.2 80  
                                 ↑ port of the webserver  
                            ↑ server's ip in esp32NAT network  
                  ↑ exposed port in the local router's network  

portmap add TCP 8080 192.168.4.2 80  
portmap add TCP 8081 192.168.4.2 81  

http://192.168.1.54:8081
http://192.168.1.54:8081/stream
