FROM nginx
#removing default html
RUN rm -rf /usr/share/nginx/html/index.html
#files should be available in current dir where docker files should be avaialble 
#COPY index.html /usr/share/nginx/html/index.html
COPY qi/ /usr/share/nginx/html/