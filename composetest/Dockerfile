FROM python:3.4-alpine
ADD . /code
WORKDIR /code
RUN pip install -r requirements.txt --proxy=http://ServiceDCSGReadonly:Readonly%40123@proxy:80
CMD ["python", "app.py"]