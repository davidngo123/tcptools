
# TCP / IP Tools

## Using Ping

### Website 1: Amazon.com
#### What were the min/avg/max/stddev statistics for each?
min/avg/max/mdev = 6.220/12.000/20.597/3.534
#### Was there any packet loss on any of the pings?
0% packet loss (so no packet loss)
#### Did the IP address change for a given website between pings?
No the IP did not change

### Website 2: Google.com
#### What were the min/avg/max/stddev statistics for each?
min/avg/max/mdev = 73.792/77.029/78.461/1.709 ms
#### Was there any packet loss on any of the pings?
No packet loss
#### Did the IP address change for a given website between pings?
The ip did not change


### Website 3: microsoft.com
#### What were the min/avg/max/stddev statistics for each?
min/avg/max/mdev = 7.172/10.558/11.975/1.728
#### Was there any packet loss on any of the pings?
No packet loss
#### Did the IP address change for a given website between pings?
No IP change

## Using "tracert"
### Website 1: Amazon.com
#### What was the target server's IP address?
18.172.169.208
#### How many hops were needed to reach the target?
Did not reach
#### Can you identify your ISP from the intermediate server DNS names?
No
#### Identify the "class" of IP address for each major step in the trip
10.0.0.1: Class A

100.92.123.67: Class A

24.153.87.25: Class A

69.139.164.81: Class A

69.139.160.249: Class A

24.124.128.121: Class A

68.86.93.9: Class A

96.110.39.226: Class A
### Website 2: Google.com
#### What was the target server's IP address?
172.217.14.196
#### How many hops were needed to reach the target?
10 hops
#### Can you identify your ISP from the intermediate server DNS names?
No
#### Identify the "class" of IP address for each major step in the trip
10.0.0.1: Class A

100.92.123.67: Class A

24.153.87.25: Class A

69.139.164.81: Class A

69.139.160.249: Class A

24.124.128.121: Class A

50.222.176.214: Class A

142.251.50.47: Class B

209.85.254.237: Class C

172.217.14.196: Class B
### Website 3: Microsoft.com
#### What was the target server's IP address?
23.45.229.117
#### How many hops were needed to reach the target?
9 hops
#### Can you identify your ISP from the intermediate server DNS names?
No 
#### Identify the "class" of IP address for each major step in the trip
10.0.0.1: Class A

100.92.123.66: Class A

24.153.87.17: Class A

69.139.160.198: Class A

69.139.164.81: Class A

24.124.128.129: Class A

69.139.160.217: Class A

96.216.153.5: Class A

23.45.229.117: Class A

### Using "ngrok"
![ngrok website](https://github.com/davidngo123/tcptools/blob/main/website.JPG)
