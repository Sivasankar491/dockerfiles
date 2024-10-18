#ARG is used to set the variables at build time only, it will not be present in container.
ARG version
#FROM almalinux:${version}
FROM almalinux:${version:-9}
ARG course="DevOps with AWS" \
    duration="120hrs"
ENV duration=${duration}
RUN echo "Course: $course, duration: $duration, version: $version"
CMD ["sleep","100"]


#ARGs can be over ridden at the time of building image.
#--build-arg <key>=<value>