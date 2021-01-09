FROM python:3.6.3

ENV SLACK_TOKEN="Debes copiar y pegar tu Token de Slack aquí"

COPY ./requirements.txt /requirements.txt

RUN pip install -r /requirements.txt

WORKDIR /nestor_slack_writer

COPY ./nestor_slack_writer.py /nestor_slack_writer.py

CMD [ "python", "/nestor_slack_writer.py" ]
