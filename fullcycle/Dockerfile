FROM golang 

WORKDIR /app/full_cycle_rocks
COPY full_cycle_rocks.go .
RUN go mod init ddias11/fullcyclerocks && go build

CMD ./fullcyclerocks
