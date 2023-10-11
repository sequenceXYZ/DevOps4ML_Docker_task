# use latest available image from DockerHub
FROM httpd:2.4.57

# copy directory from local macine to container
COPY ./website/ /usr/local/apache2/htdocs/

# listen for traffic on the specified port
EXPOSE 15100