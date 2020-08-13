# Use Python Image
FROM python:3.7
# Install apt dependencies
RUN apt install python3 python3-pip
# Copy contents into image
COPY . .
# run pip dependencies
RUN pip3 install flask flask_sqlalchemy SQLAlchemy pymysql
# Expose correct port
EXPOSE 5000
# Create an entrypoint
ENTRYPOINT ["python3", "app.py"]
