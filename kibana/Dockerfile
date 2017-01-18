FROM kibana:4.3.1

RUN apt-get update && apt-get install -y netcat

COPY entrypoint.sh /tmp/entrypoint.sh
RUN chmod +x /tmp/entrypoint.sh

RUN kibana plugin --install elastic/sense

EXPOSE 5601
CMD ["/tmp/entrypoint.sh"]
