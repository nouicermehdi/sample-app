FROM python
RUN pip install flask
COPY  ./static /home/myapp/static/
COPY  ./templates /home/myapp/templates/
COPY  sample_app.py /home/myapp/
EXPOSE 8080
CMD python /home/myapp/sample_app.py
FROM python:3.11-slim
RUN pip install flask
COPY  ./static /home/myapp/static/
COPY  ./templates /home/myapp/templates/
COPsY  sample_app.py /home/myapp/
EXPOSE 5050
CMD python /home/myapp/sample_app.py
