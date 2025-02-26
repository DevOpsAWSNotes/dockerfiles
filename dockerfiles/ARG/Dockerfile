FROM almalinux:9
ENV course="devops with AWS" \
    learner="gowtham" \
    duration="120 hrs"
# here username is key, some_user is value
ARG ${username:-some_user}
RUN echo "Hello ${username}" > /tmp/devops.txt
CMD ["sleep","100"]