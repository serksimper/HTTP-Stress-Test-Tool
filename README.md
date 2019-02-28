# HTTP-Stress-Test-Tool
Simple Python 3.7 script to send a lot of HTTP GET Requests using Requests and Multiprocessing libraries 

Use with extreme caution

This script was created while learning about python multiprocessing.  

By design this script will make use of all processor cores on the server at max utility

**This is not a serious project.**

# Testing Output Examples
All tests performed on Ubuntu 16.04 w/ 10 vCPUs 32GB RAM 

### 1,002 HTTP GET Requests
Started HTTP Stress Test @ Wed, 27 Feb 2019 19:29:20

Stopped HTTP Stress Test @ Wed, 27 Feb 2019 19:29:20

Sent 1,002 HTTP GET Requests in 0.32366013526916504 seconds

### 10,002 HTTP GET Requests
Started HTTP Stress Test @ Wed, 27 Feb 2019 19:28:00

Stopped HTTP Stress Test @ Wed, 27 Feb 2019 19:28:03

Sent 10,002 HTTP GET Requests in 2.528158187866211 seconds

### 100,002 HTTP GET Requests
Started HTTP Stress Test @ Wed, 27 Feb 2019 19:31:01

Stopped HTTP Stress Test @ Wed, 27 Feb 2019 19:31:24

Sent 100,002 HTTP GET Requests in 22.78402829170227 seconds

### 1,000,002 HTTP GET Requests
Started HTTP Stress Test @ Wed, 27 Feb 2019 19:33:43

Stopped HTTP Stress Test @ Wed, 27 Feb 2019 19:37:33

Sent 1,000,002 HTTP GET Requests in 229.37944889068604 seconds
