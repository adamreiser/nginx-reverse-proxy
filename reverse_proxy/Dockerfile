FROM nginx
ADD ./reverse_proxy.template /etc/nginx/conf.d/reverse_proxy.template
CMD ["/bin/bash", "-c", "envsubst '$$NGINX_HOST $$NGINX_PORT $$BACKEND_PORT' < /etc/nginx/conf.d/reverse_proxy.template > /etc/nginx/conf.d/default.conf && nginx -g 'daemon off;'"]
