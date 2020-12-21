FROM python
WORKDIR /app
ADD ./yes.svg ./
CMD ["python", "-mhttp.server", "${BACKEND_PORT}"]
