**CONFIGURE APACHE AS A LOAD BALANCER**

**![apacheinstalled](./images/apacheinstalled.PNG)**

**Verify that my configuration works – Accessing my LB’s public IP address or Public DNS name from your browser**

**![loadbalancerworks](./images/lbworks.PNG)**

**using the command below to see who access our server**

**sudo tail -f /var/log/httpd/access_log**

**![serveraccess](./images/serveraccess.PNG)**

**curl your Web Servers from LB locally curl http://Web1 or curl http://Web2**

**![curlwebserver](./images/curl%20webser.PNG)**




