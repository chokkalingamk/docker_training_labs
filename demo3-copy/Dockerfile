FROM nginx:alpine
LABEL maintainer="bootlabs"

COPY index.html /usr/share/nginx/html/
ENTRYPOINT ["nginx", "-g", "daemon off;"] 


###############Multistage################

# FROM alpine AS stage1
# LABEL maintainer="bootlabs"
# RUN echo "Welcome to docker training Labs!" > /opt/index.html

# FROM nginx:alpine
# LABEL maintainer="bootlabs"
# COPY --from=stage1 /opt/index.html /usr/share/nginx/html/
# ENTRYPOINT ["nginx", "-g", "daemon off;"]