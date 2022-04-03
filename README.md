# docker-nginx-hello-world
Single page docker nginx 

**Note:**
This repository is for testing Google Cloud Build and how code commits affect the CI/CD pipeline. No security or usefulness considerations whatsoever are made.
Also used to build local/cloud CI/CD pipeline.

NGINX webserver that serves a simple page containing its hostname, IP address and port as wells as the request URI and the local time of the webserver.

The images are uploaded to Docker Hub -- https://hub.docker.com/r/dockerbogo/docker-nginx-hello-world/.

How to run:
```
$ docker run -p 8080:80 -d dockerbogo/docker-nginx-hello-world
```

Now, assuming we found out the IP address and the port that mapped to port 80 on the container, in a browser we can make a request to the webserver and get the page below: 

![hello_world](./hello_world.png)


Reference: [Docker & Kubernetes](http://bogotobogo.com/DevOps/Docker/Docker_Kubernetes.php)
