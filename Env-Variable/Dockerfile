FROM busybox
ENV NGINX 1.2
RUN mkdir -p /root/folder1
WORKDIR /root/folder1
RUN touch file-${NGINX}.txt
CMD ["sh"]