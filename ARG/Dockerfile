FROM almalinux:8
ARG username
RUN adduser ${username}
USER ${username}
CMD["sleep", "100"]

# ARG only able to access on build time
# ENV variable able to access container level


### Important rule
# IF you use ARG command before FROM command after FROM command you cannot access

ARG version
FROM almalinux:${version}
RUN echo "version ${version}" # here version will not avaiable to access due to ran in before from command