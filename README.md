# kube-docker

Build the docker image from the Dockerfile present inside MathApp folder.

and then run the container using

# docker run -it --rm --name ma-instance -p 8080:8080 \
#   -v /app/MathApp:/go/src/MathApp -w /go/src/MathApp ma-image

# To see the app running, go to the url followed 
# http://url-where-container-is-running:8080/sum/4/5

will return the result.


# Maintainer
Shoaib
