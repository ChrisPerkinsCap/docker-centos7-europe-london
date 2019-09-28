FROM centos:7

LABEL maintainer="christopher.perkins@capgemini.com"

# Set the local timezone to BST
RUN rm -f /etc/localtime \
    && ln -s /usr/share/zoneinfo/Europe/London /etc/localtime

CMD ["date"]
