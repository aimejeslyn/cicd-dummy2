FROM nginx:stable-alpine
#hapus config default nginx
RUN rm /etc/nginx/conf.d/default.conf
#copy nginx.conf sebagai config default nginx
COPY /nginx/nginx.conf /etc/nginx/conf.d/default.conf
