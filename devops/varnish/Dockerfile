# syntax=docker/dockerfile:1
FROM varnish:7.6

LABEL maintainer="Lucas Aquino <lucas@lucasaquino.com.br>" \
      org.label-schema.name="pai-poeta-varnish" \
      org.label-schema.description="Pai Poeta Varnish image." \
      org.label-schema.vendor="Lucas Aquino"

COPY etc/varnish.vcl /etc/varnish/default.vcl
