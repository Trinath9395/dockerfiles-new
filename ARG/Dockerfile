ARG version
FROM almalinux:${version:-9}
ENV course="Devops with AWS" \
    trainer="Trinath Reddy" \
    duration="120HR"
ARG USERNAME=Trinath
ENV USERNAME=${USERNAME}
RUN echo "Hello User: ${USERNAME} image version: ${version}" > /tmp/devops.txt 
CMD ["sleep", "100"]
