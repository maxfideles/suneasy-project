# SunEasy

## Overview
I'm currently developing a full-stack project that serves as a comprehensive catalog for Solar Panels and Inverters. To achieve high scalability and maintain a robust architecture, we have chosen to leverage **Spring Boot** to implement a microservices approach.

The project is designed with horizontal scalability in mind, and for that purpose, I am utilizing Nginx as both a Reverse Proxy and a Load Balancer. Additionally, I have incorporated Redis for caching, enhancing the overall performance and responsiveness of our application.

Access the [Backend](https://github.com/maxfideles/suneasyapi) and [Frontend](https://github.com/maxfideles/suneasy)


## System Design
<img width="1264" alt="image" src="https://github.com/maxfideles/suneasy-project/assets/61297641/a0eba91e-da33-4c74-b457-96c05fd8359e">

## Setting Up

### Nginx

On this project, Nginx serves a dual purpose: acting as a reverse proxy and providing load balancing capabilities. If you want to learn how to set up Nginx for your project, I have created a helpful [video tutorial](https://www.youtube.com/watch?v%253Dqq8lwam52ns), which you can access here. 

Additionally, the Nginx configuration file (nginx.conf) can be found on our GitHub repository [here](https://github.com/maxfideles/suneasy-project/blob/main/nginx.conf).


### Redis

Redis plays a crucial role as a shared cache, providing swift responses for data that remains static. It's a key component for optimizing performance.

 I've created an informative [video tutorial](https://youtu.be/2B2FnELOoWI). I'll guide you through the essentials of Redis and demonstrate how to install and configure it to enhance the performance of the Suneasy Project.
