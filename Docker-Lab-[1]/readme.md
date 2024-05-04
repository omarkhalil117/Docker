# Lab [1]

### 1) Create a container from hello-world image and set its name to first-container.
![Link Name](images/1.1.png)  
![Link Name](images/1.2.png)  

### 2) Create two containers from nginx image, run the first one in the foreground and the second one in the background.
![Link Name](images/2.1.png)  
![Link Name](images/2.2.png)  

### 3) Download bitnamimages/laravel image (version 9.5.2) 
###    - List all images 
###    - Remove laravel image 
 
![Link Name](images/3.1.png)  
![Link Name](images/3.2.png)  

### 4) Create a container from httpd image 
###    Map apache server running on the container to port 82 on your local machine
###    Check that it is working using your browser


![Link Name](images/4.1.png)  
![Link Name](images/4.2.png)  

### 5) Create file inside foreground container then list all files (use interactive mode)
### Remove this container 

![Link Name](images/5.1.png)  
![Link Name](images/5.2.png)  

### 6) Printimages/etc/hosts file from background container (without interactive mode)

![Link Name](images/6.png)  

### 7) Create mysql container, map tmp directory (on your local machine) toimages/var/lib (on the container).


![Link Name](images/7.png)  

### 8) Create a volume lab1, start two containers from nginx image and mount this volume toimages/app, create a file from the first container on the path mapped to this volume and check that it exists on the second container.

![Link Name](images/8.png)  