FROM node

COPY src /src/
WORKDIR /src/

RUN npm install -g truffle && npm install && npm install ipfs-api  

ENTRYPOINT ["sh", "launch.sh"]
