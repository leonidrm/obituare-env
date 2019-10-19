FROM nginx:1.12-alpine
# set main params
RUN ln -sf /dev/stdout /var/log/nginx/access.log && \
    ln -sf /dev/stderr /var/log/nginx/error.log && \
    rm -rf /etc/nginx/conf.d/*

COPY ./wordpress.conf /etc/nginx/conf.d/