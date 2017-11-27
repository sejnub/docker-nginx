# Info

# Build

````
cd ~
rm -rf docker-nginx
git clone https://github.com/sejnub/docker-nginx.git
cd ~/docker-nginx/raspbian 
docker build -t sejnub/nginx .
````


# Run

````
docker rm -f nginx; docker run --net host -it --env-file /usr/local/etc/sejnub-credentials.env --name dash sejnub/amazon-dash-sniff /bin/bash
````


eof
