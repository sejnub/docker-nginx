FROM tobi312/rpi-nginx


RUN apt-get update               && \
    apt-get install -yqq jq      && \
    apt-get install -yqq sshpass
    
    
    
CMD ["nginx", "-g", "daemon off;"]
