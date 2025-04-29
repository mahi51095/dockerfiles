FROM almalinux:8
RUN yum install epel-release -y
RUN yum install -y nginx
RUN echo "Hello,Dockerfile.Way of creating img's" > /usr/share/nginx/hello.html
CMD [ "nginx", "-g","daemon off"]
