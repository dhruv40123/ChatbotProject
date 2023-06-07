FROM python:3.9
EXPOSE 5612
ADD model.tar.gz models/model.tar.gz
ENTRYPOINT rasa run -m models/model.tar.gz --cors "*" ; rasa run actions
