# NGINX 

This Repository sets up an NGINX Configuration file for different aspect of Nginx as nginx can be used as loadbalancer ,webserver.

Follow the steps below to build and run the container.

---

## Step-by-Step Instructions

### 1. Clone the Repository
First, clone this repository to your local machine:
```
git clone https://github.com/HATAKEkakshi/Nginx-.git
```
### 2. Load Balancer
```
    cd Load\ Balancer/
```
#### 1. Building the Container
```
    docker build -t nginx-load-balancer .

```
#### 2. Running the Container
```
    docker run -d -p 80:80 --name my-nginx-loadbalancer nginx-load-balancer


```
