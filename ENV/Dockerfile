FROM almalinux:9
RUN dnf install nginx -y
CMD ["nginx", "-g", "daemon off;"]
EXPOSE 80
ENV MONGO_URL="mongodb-dev.rkak87.online" \
    MONGO_USER="admin"