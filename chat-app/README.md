# backend api for chat application 
provides functionality for login,signup,one-on-one chat,group chat

# dockerfile is provided
to build Image from dockerfile
```
    docker build -t <image_name_you_want_to_give> .
```
to check image 
```
    docker images
```

to run the container in detach node(background)
```
    docker run -d -p 3000:3000 <image_name>
```