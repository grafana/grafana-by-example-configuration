FROM python:3

WORKDIR /usr/src/app

COPY requirements.txt ./
COPY metrics-generator.py ./
RUN pip install --no-cache-dir -r requirements.txt


#ENTRYPOINT [ "sleep", "3600" ]
#ENTRYPOINT [ "python", "--version" ]
ENTRYPOINT [ "python", "metrics-generator.py", "regionalServices" ] 