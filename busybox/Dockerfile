FROM busybox
RUN adduser -D user
#USER root #gets denied fine
#USER root:root #fixed
#USER 0:0 #fixed
#USER root:0 #fixed
#USER 0:root #fixed
USER user

#docker tag distribution_busybox localhost:5000/distribution_busybox
#docker push localhost:5000/distribution_busybox && echo done
#docker rmi localhost:5000/library/busybox:1.29.3-musl -f && docker run -it localhost:5000/library/busybox:1.29.3-musl
