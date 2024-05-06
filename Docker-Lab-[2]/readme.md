# Lab 2



## 1.Create an image to containerize a simple php app that prints hello world, use apache server

![Link Name](images/1.1.png)
![Link Name](images/1.2.png)  


### Push this image to docker hub 

#### create repo
![Link Name](images/1.3.png)
#### push the image into repository  
![Link Name](images/1.4.png)  
#### pushed successully into repo !!
![Link Name](images/1.5.png)  

### Remove it from your local machine
![Link Name](images/1.6.png)  

### Use the image you uploaded to create a container that works on port 80
![Link Name](images/1.7.png)  
![Link Name](images/1.8.png)  



## 2.Write a Dockerfile, use ubuntu as the base image and use CMD to echo hello user.

![Link Name](images/2.1.png)

### Create two containers from this image, create the first one without passing a parameter and use ls command as the parameter when creating the second one

![Link Name](images/2.2.png)

### Do the same as the last question but use ENTRYPOINT.

![Link Name](images/2.3.png)
![Link Name](images/2.4.png)

### Use both cmd and entrypoint to echo hello + the parameter passed

![Link Name](images/2.5.png)
![Link Name](images/2.6.png)

 
## 3.Host a react application on nginx. (Use multi-stage dockerfile).


![Link Name](images/3.1.png)
![Link Name](images/3.2.png)
![Link Name](images/3.3.png)
![Link Name](images/3.4.png)