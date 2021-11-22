FROM python:3.9
ENV DASH_DEBUG_MODE True    
LABEL maintainer "James Wyrick jwyrick4@gmu.edu"
RUN mkdir /code
WORKDIR /code

COPY requirements.txt /code/
RUN pip install -r /code/requirements.txt
COPY . /code/
EXPOSE 8050
CMD ["python", "/code/cds303-model.py"]
