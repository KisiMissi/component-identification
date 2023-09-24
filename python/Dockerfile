FROM python

RUN pip install ultralytics
RUN pip install pillow

COPY . /app

WORKDIR /app

CMD ["python", "predictTest.py"]
