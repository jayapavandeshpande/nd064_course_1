FROM python:2.7
COPY . /app
WORKDIR /app
RUN python -m pip install --upgrade pip
RUN pip install -r requirements.txt
RUN python init_db.py
CMD [ "python", "app.py" ]
EXPOSE 3111
