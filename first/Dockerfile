FROM nginx:alpine

WORKDIR /usr/share/nginx/html
RUN rm -rf ./*
COPY ./* ./

EXPOSE 80

HEALTHCHECK --interval=2s --timeout=5s --retries=5 CMD curl -f http://localhost:80 || exit 1

<<<<<<< HEAD
ENTRYPOINT ["sh", "entrypoint.sh"]
=======
ENTRYPOINT ["sh", "entrypoint.sh"]
# ENTRYPOINT ["nginx", "-g", "daemon off;"]
# CMD ["echo", "Connection Established"]
>>>>>>> 24ee709f0a4c3698705bed49a6270e700f791edb
