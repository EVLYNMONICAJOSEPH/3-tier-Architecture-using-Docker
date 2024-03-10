FROM python:3
RUN mkdir /code
WORKDIR /code
ADD requirements.txt /code/
RUN pip3 install -r requirements.txt
ADD . /code/
EXPOSE 5001
ENV FLASK_APP=front.py
CMD ["python3", "-m" , "flask", "run", "front.py" ]
