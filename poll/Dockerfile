FROM python:3
WORKDIR /usr/src/app
COPY requirements.txt ./
RUN pip3 install --no-cache-dir -r requirements.txt
COPY . .
EXPOSE 80
CMD ["flask", "run", "--host=0.0.0.0", "--port=80"]
