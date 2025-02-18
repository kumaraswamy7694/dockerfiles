ARG version
FROM almalinux:${version:-8}
#variable before from will now work after form 
RUN echo "version passed by user is: ${version}"
ARG COURSE
ARG TRAINER
RUN echo "couse is: ${COURSE}, trainer is: ${TRAINER}"