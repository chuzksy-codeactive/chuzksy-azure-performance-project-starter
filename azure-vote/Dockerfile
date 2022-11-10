# Pull the base image
FROM tiangolo/uwsgi-nginx-flask:python3.6
# Install depndencies 
RUN pip install redis
RUN pip install opencensus
RUN pip install flask
RUN pip install certifi
RUN pip install charset-normalizer
RUN pip install click
RUN pip install colorama
RUN pip install Flask
RUN pip install google-api-core
RUN pip install google-auth
RUN pip install googleapis-common-protos
RUN pip install cryptography
RUN pip install idna
RUN pip install itsdangerous
RUN pip install Jinja2
RUN pip install MarkupSafe
RUN pip install opencensus
RUN pip install opencensus-context
RUN pip install opencensus-ext-azure
RUN pip install opencensus-ext-flask
RUN pip install opencensus-ext-logging
RUN pip install opencensus-ext-requests
RUN pip install protobuf
RUN pip install psutil
RUN pip install pyasn1
RUN pip install pyasn1-modules
RUN pip install redis
RUN pip install requests
RUN pip install rsa
RUN pip install six
RUN pip install urllib3
RUN pip install Werkzeug
RUN pip install wrapt

# Copy the content of the current directory to the /app of the container
ADD . /app
