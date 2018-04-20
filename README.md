# McAfee-Client-Proxy-bypass
McAfee Client Proxy bypass

Proxy bypass in McAfee Client Proxy 2.3.2.251 allows local users to bypass the McAfee Client Proxy via local IP address changes, being possible to bypass the McAfee Client Proxy without using an administrator-generated security key in contrast to the McAfee Client Proxy's faq (https://www.mcafee.com/es/resources/faqs/faq-client-proxy.pdf) 

Evidences:

Local IP: 192.168.1.117 --> Traffic is redirected.
![alt text](https://github.com/juanrafaelvillen/McAfee-Client-Proxy-bypass/blob/master/mcafeevuln.png?raw=true)

Changing local ip to 192.168.1.99 --> bypassing The McAfee Client Proxy
![alt text](https://github.com/juanrafaelvillen/McAfee-Client-Proxy-bypass/blob/master/mcafee2.png?raw=true)
