FROM hodumi/docker-roswell

# Make & Open Project Dir
RUN mkdir /project
COPY start.ros /project
VOLUME /project


# Run PROJECT
EXPOSE 4005

ENTRYPOINT ["/project/start.ros", "4005"]