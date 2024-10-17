FROM almalinux:9
RUN mkdir /opt/app
WORKDIR /opt/app
RUN echo "hello world" > hello.txt
CMD [ "sleep", "100" ]
#cd command usually doesn't work in docker files, instead we use WORKDIR instruction.