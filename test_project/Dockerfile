FROM python:3.12.4
ENV PYTHONDONTWRITEBYTECODE 1
ENV PYTHONUNBUFFERED 1


WORKDIR /app
ADD ./requirements.txt /app/requirements.txt
RUN python -m pip install --upgrade pip
RUN pip install -r requirements.txt
ADD . /app
CMD python manage.py migrate --no-input && python manage.py runserver 0.0.0.0:8000

