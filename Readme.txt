# Steps 

1. use dockerfile to package the application 
2. Start from a specific image 
3. COPY the files in current dir (.) into the dir in the image (/app)
4. WORKDIR set the current dir to the dir in the image 
5. CMD execute the commands   
6. GO TO terminal to package the app (docker built -t (give the image a tag to identify) [tag name] [where docker can find the dockerfile])
7. IMAGE is not stored as a file under the dir. USE docker image ls to check the info about the image 
