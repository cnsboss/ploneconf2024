# syntax=docker/dockerfile:1
FROM varnish:7.6

LABEL maintainer="Cassio Santiago <cassio.santiago@senado.leg.br>" \
      org.label-schema.name="ploneconf2024-varnish" \
      org.label-schema.description="Plone Conference Training Varnish image." \
      org.label-schema.vendor="Cassio Santiago"

COPY etc/varnish.vcl /etc/varnish/default.vcl
