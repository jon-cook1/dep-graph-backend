FROM python:3.12-slim-bookworm

WORKDIR /app

COPY requirements.txt .

RUN pip install -r requirements.txt

COPY . .


CMD ["fastapi","run","graphAPI.py","--port","80"]


#build image:
#docker build -t backend .

#run container:
#docker run -d --name container -p 80:80 backend