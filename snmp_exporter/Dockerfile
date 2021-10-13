FROM golang:1.16-alpine

RUN mkdir /snmp_exporter
#COPY ./snmp_exporter /snmp_exporter
WORKDIR /snmp_exporter

CMD ["./snmp_exporter"]
#CMD ["./snmp_exporter","--log.level=debug"] #if need check detail logs
