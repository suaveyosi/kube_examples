FROM nginx:latest
LABEL maintainer="Vid"
# We can define vars. We will define them using deployment in k8s
#ENV CONTENT="eres muuuuy feo" \
#    PORT=80r
COPY default.conf /etc/nginx/conf.d/
RUN echo ${CONTENT} > /usr/share/nginx/html/index.html
EXPOSE ${PORT}