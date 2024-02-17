FROM python
EXPOSE 8080
WORKDIR /app
COPY ./ /app
RUN pip install -r requirements.txt

ENTRYPOINT [ "python", "/app/hello-world.py"]

