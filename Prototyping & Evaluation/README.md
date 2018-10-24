# The task

There are three digital ocean droplets that are all set up to respond to ping, which are given by the task:
- 128.199.144.199
- 167.99.51.33
- 46.101.253.149


# Behavior of ping times of these three servers

The response time is depend on distance between server and request point (client). According to this relativity, with longer distance, respons time would increase.

# Expriment has done through the following approach: 

Response time and distance to server has been measured in a paticular location. Experiment has repeatet in another particular location. Comparing the distances to several servers and also compare the data which are provided from to particular location, shows the response time clearly.

```sh

GERMANY- Gentofte


Pinging 46.101.253.149 with 32 bytes of data:
Reply from 46.101.253.149: bytes=32 time=17ms TTL=51
Reply from 46.101.253.149: bytes=32 time=20ms TTL=51
Reply from 46.101.253.149: bytes=32 time=20ms TTL=51
Reply from 46.101.253.149: bytes=32 time=20ms TTL=51

Ping statistics for 46.101.253.149:
    Packets: Sent = 4, Received = 4, Lost = 0 (0% loss),
Approximate round trip times in milli-seconds:
    Minimum = 17ms, Maximum = 20ms, Average = 19ms
    
USA- Gentofte


Pinging 167.99.51.33 with 32 bytes of data:
Reply from 167.99.51.33: bytes=32 time=109ms TTL=52
Reply from 167.99.51.33: bytes=32 time=125ms TTL=52
Reply from 167.99.51.33: bytes=32 time=95ms TTL=52
Reply from 167.99.51.33: bytes=32 time=98ms TTL=52

Ping statistics for 167.99.51.33:
    Packets: Sent = 4, Received = 4, Lost = 0 (0% loss),
Approximate round trip times in milli-seconds:
    Minimum = 95ms, Maximum = 125ms, Average = 106ms
    


Singapore- Gentofte


Pinging 128.199.144.199 with 32 bytes of data:
Reply from 128.199.144.199: bytes=32 time=268ms TTL=45
Reply from 128.199.144.199: bytes=32 time=269ms TTL=45
Reply from 128.199.144.199: bytes=32 time=268ms TTL=45
Reply from 128.199.144.199: bytes=32 time=268ms TTL=45

Ping statistics for 128.199.144.199:
    Packets: Sent = 4, Received = 4, Lost = 0 (0% loss),
Approximate round trip times in milli-seconds:
    Minimum = 268ms, Maximum = 269ms, Average = 268ms

```

```sh
GERMANY- Lyngby


Pinging 46.101.253.149 with 32 bytes of data:
Reply from 46.101.253.149: bytes=32 time=17ms TTL=51
Reply from 46.101.253.149: bytes=32 time=17ms TTL=51
Reply from 46.101.253.149: bytes=32 time=17ms TTL=51
Reply from 46.101.253.149: bytes=32 time=20ms TTL=51

Ping statistics for 46.101.253.149:
    Packets: Sent = 4, Received = 4, Lost = 0 (0% loss),
Approximate round trip times in milli-seconds:
    Minimum = 17ms, Maximum = 20ms, Average = 17ms
    
USA- Lyngby


Pinging 167.99.51.33 with 32 bytes of data:
Reply from 167.99.51.33: bytes=32 time=108ms TTL=53
Reply from 167.99.51.33: bytes=32 time=109ms TTL=53
Reply from 167.99.51.33: bytes=32 time=109ms TTL=53
Reply from 167.99.51.33: bytes=32 time=109ms TTL=53

Ping statistics for 167.99.51.33:
    Packets: Sent = 4, Received = 4, Lost = 0 (0% loss),
Approximate round trip times in milli-seconds:
    Minimum = 108ms, Maximum = 109ms, Average = 108ms



Singapore- Lyngby


Pinging 128.199.144.199 with 32 bytes of data:
Reply from 128.199.144.199: bytes=32 time=348ms TTL=42
Reply from 128.199.144.199: bytes=32 time=348ms TTL=42
Reply from 128.199.144.199: bytes=32 time=348ms TTL=42
Reply from 128.199.144.199: bytes=32 time=345ms TTL=42

Ping statistics for 128.199.144.199:
    Packets: Sent = 4, Received = 4, Lost = 0 (0% loss),
Approximate round trip times in milli-seconds:
    Minimum = 345ms, Maximum = 348ms, Average = 347ms
 ```   
    
    
- ping 128.199.144.199 >> singaphour.txt
- ping 46.101.253.149 >> germany.txt
- ping 167.99.51.33 >> usa.txt


# Measures response times of these three servers

First I have found where this ip belong to and also the distance between my location to the places where ip locations are. 
So I've pinged from 2 different loction to the 3 ip addresses.

so I could see the average for the first location is different from the next loction. 
Due to it's distance between 2 locations

- Resource : 
```sh
The website to find the location of particular ip:
 ```
 
 https://tools.keycdn.com/geo

```sh
```

![alt text](https://user-images.githubusercontent.com/20173643/47400980-b8509380-d73f-11e8-8a8d-d4d6af6f7708.PNG)
![alt text](https://user-images.githubusercontent.com/20173643/47400983-bb4b8400-d73f-11e8-8090-a5feef6dcaf4.PNG)
![alt text](https://user-images.githubusercontent.com/20173643/47400986-bc7cb100-d73f-11e8-9ef3-be26e5e4842b.PNG)

```sh


The website to calculate the distance from server location, which is found from the website mentioned before :

```
https://www.distancecalculator.net/


```sh
```
![alt text](https://user-images.githubusercontent.com/20173643/47400988-be467480-d73f-11e8-8741-fbbc9ce0d1fd.PNG)
![alt text](https://user-images.githubusercontent.com/20173643/47400989-bf77a180-d73f-11e8-84b4-c5210abd82f3.PNG)
![alt text](https://user-images.githubusercontent.com/20173643/47400990-c1416500-d73f-11e8-861a-6c7660581a35.PNG)
