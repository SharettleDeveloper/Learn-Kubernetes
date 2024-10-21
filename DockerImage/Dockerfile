FROM golang:1.18

RUN mkdir /echo
RUN cat /tmp/version
COPY main.go /echo
CMD ["go","run","/echo/main.go"]

