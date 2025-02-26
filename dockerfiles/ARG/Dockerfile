ARG version
FROM almalinux:${version:-9}
ENV course="devops with AWS" \
    learner="gowtham" \
    duration="120 hrs"
# here username is key, some_user is value
ARG USERANAME=Gowtham521
ENV USERNAME=$USERANAME
RUN echo "Hello USER: ${USERANAME}, imge version {version}" > /tmp/devops.txt 
CMD ["sleep","100"]