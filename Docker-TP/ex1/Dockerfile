FROM alpine:3.12
#installation de git /curl
RUN apk update
RUN apk add git
RUN apk add curl
# commande de demmarage
CMD ["sh","-c","git --version && curl --version"]

