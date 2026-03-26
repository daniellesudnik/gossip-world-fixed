FROM python:3.8
WORKDIR /app
ADD app/requirements.txt /app/requirements.txt
RUN pip install -r requirements.txt
USER nobody
CMD python routes.py

