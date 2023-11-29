FROM python:latest
COPY ./requirements.txt /app/requirements.txt
WORKDIR /app
RUN pip install -r requirements.txt
ADD . ./
ENV PYTHONPATH /app
RUN ls
EXPOSE 5000
ENTRYPOINT ["python", "Controller/app.py" ]
