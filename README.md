Consul
=========  

### Build Consul image  
make **VERSION=0.6**

### Running image  
sudo docker run -p 8500:8500 -p 5300:53/udp -h node1 lindep/consul:0.6 -server -bootstrap

From web interface  
localhost:8500  
Get IP of the consul service

dig @172.17.0.6 consul.service.consul
