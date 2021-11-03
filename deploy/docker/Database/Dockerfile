FROM mongo:3.4

MAINTAINER juliens@microsoft.com

COPY drop/* usr/local/data/db/

CMD ["mongod", "--smallfiles", "--rest"]