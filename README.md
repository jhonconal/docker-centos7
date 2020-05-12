### A sample docker build based on centos7.6

### Instruction

```
#Dockerfile directory 
Step A: docker build -t  centos7.6 `pwd` 
#run test
Step B: docker run -it --name centos7.6 uname/centos7.6 
# set tag for your docker images,uname(your dockerhub account)
Step C: docker tag centos7.6 uname/centos7.6 
# push local image to your dockerhub
Step D: docker push uanme/centos7.6
```

