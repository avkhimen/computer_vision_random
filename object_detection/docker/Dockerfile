# Base image of your application
FROM bitnami/pytorch

# Copy requirements.txt file into your image
COPY /requirements.txt /

# Install packages from requirements.txt file
RUN pip install -r /requirements.txt