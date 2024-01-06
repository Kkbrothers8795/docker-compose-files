FROM mongo:5.0.6-focal

RUN mkdir $HOME/uzrnem/database/mongo_db:/data/db
RUN mkdir $HOME/uzrnem/database/backup:/backup
RUN chmod -R 777 $HOME/uzrnem/

VOLUME $HOME/uzrnem/database/backup:/backup
VOLUME $HOME/uzrnem/database/mongo_db:/data/db

EXPOSE 27017:27017

ENV MONGO_INITDB_ROOT_USERNAME=root
ENV MONGO_INITDB_ROOT_PASSWORD=Kkraju00123a

