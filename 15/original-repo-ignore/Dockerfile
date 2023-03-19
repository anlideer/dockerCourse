FROM python:3.8
EXPOSE 5000
WORKDIR /usr/src/app
RUN pip install flask
COPY app.py .
CMD ["python3", "app.py"]