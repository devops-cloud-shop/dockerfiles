ARG VERSION
FROM almalinux:${VERSION:-9}  

##This is an exceptional case, ARG can be the first instruction
# where it is used to change/supply the version to the BASE image
#If we dont supply the version it takes the default 9.

ARG COURSE="DevOps" \
    TRAINER="Siva" \
    DURATION="10HRS"
RUN echo "Trainer: ${TRAINER}, Course: ${COURSE}"
CMD ["sleep", "200"]