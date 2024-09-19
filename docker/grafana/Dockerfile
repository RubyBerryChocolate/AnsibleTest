FROM grafana/grafana-enterprise:latest
USER root
RUN apk upgrade --no-cache && apk add --no-cache python3 py3-pip
ENTRYPOINT ["/run.sh"]
