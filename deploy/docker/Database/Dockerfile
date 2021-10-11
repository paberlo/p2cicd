FROM mongo

MAINTAINER juliens@microsoft.com

COPY drop/* usr/local/data/db

CMD ["mongod", "--smallfiles", "--rest"]