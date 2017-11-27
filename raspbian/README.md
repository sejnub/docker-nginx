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
docker rm -f nginx; docker run --env-file /usr/local/etc/sejnub-credentials.env --name nginx sejnub/nginx
````


eof
