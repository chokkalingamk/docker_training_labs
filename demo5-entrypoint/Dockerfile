# FROM alpine:3.16
# LABEL maintainer="Bootlabs"

# # ENTRYPOINT ["/bin/echo", "Hi, your ENTRYPOINT instruction in Exec Form !"]


# ENTRYPOINT echo "Hi, This Entrypoint instruction is in Shell Form !!!"

#########################################

FROM ubuntu
RUN apt-get update
RUN apt-get install -y wget
ENTRYPOINT [ "wget", "-O-", "-q" ]
CMD http://ifconfig.me/ip