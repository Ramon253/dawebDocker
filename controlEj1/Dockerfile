FROM node:14
RUN apt update && apt install git
WORKDIR /var/app
RUN git clone https://github.com/ramon253/NodeDocker.git
WORKDIR /var/app/NodeDocker
RUN npm install

CMD ["/bin/bash"]