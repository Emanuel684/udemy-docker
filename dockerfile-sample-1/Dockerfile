FROM nginx:latest
# highly recommend you always pin versions for anything beyond dev/learn

WORKDIR /usr/share/nginx/html
# change working directory to root of nginx webhost
# using WORKIR is prefered to using RUN cd /some/path

COPY index.html index.html

# I idont have to specify EXPOSE or CMD because there in my FROM

