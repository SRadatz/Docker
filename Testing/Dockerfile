FROM python:3.6-alpine

COPY index.py /index.py
COPY entrypoint.sh /entrypoint.sh

RUN chmod +X index.py

CMD ["/entrypoint.sh"]
