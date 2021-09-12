FROM debian:stretch-slim

RUN apt-get update && apt-get install -y curl

WORKDIR /app

COPY script.sh .

ENTRYPOINT ["/bin/bash", "script.sh"]

CMD ["https://localhost"]
