# bsidejeddah-PCAP

| item         | description                                                                  |
| ------------ | ---------------------------------------------------------------------------- |
| SHA1SUM      | c1995aff38c8947a2555e575e1cef2df3c4f888e                                     |
| Published    | Nov. 25, 2021                                                                |
| Author       | CyberDefenders                                                               |
| Size         | 46 MB                                                                        |
| Tags         | WIRESHARKPCAPMALWARE ANALYSISTHREAT HUNTINGCVES                              |
| Instructions | Uncompress the challenge (pass: {Please login the website to get password} ) |


## Challnge Questions

### 1. What is the victim's MAC address?

#### Step 1
Find more traffic in EndPoints View
![](./Images/Screen%20Shot%202021-12-05%20at%201.32.42%20PM.png)

I found the 23.205.8.23 which has much packets, so I select it to filter.


#### Step 2 

Then I observe the packets, the 192.168.128.139 use many port send traffic to 443 port of 23.205.8.23's service. So We can ensure the victim is 192.168.128.139.

The answer must input the MAC of IP address, so we could see the detail view to check MAC.

![](./Images/Screen%20Shot%202021-12-05%20at%201.44.00%20PM.png)


ANS: 00:0c:29:b7:ca:91

ds