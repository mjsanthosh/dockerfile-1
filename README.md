# dockerfile
This Docker File in CentOS-Gui is of Centos with SSh Enabled Container
run the following Command to build and deploy the container

docker build -t "Jenkins build 3" .

docker container run -it --name=ssh -p 2222:22 "Image Name" bash
