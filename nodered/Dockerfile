FROM nodered/node-red:1.2.7
USER root

WORKDIR /usr/src/node-red

RUN npm install node-red-contrib-iiot-opcua
#RUN npm install node-red-dashboard
#RUN npm install node-red-node-mongodb
#RUN npm install @mindconnect/node-red-contrib-mindconnect
#RUN npm install node-red-node-email
#RUN npm install node-red-contrib-opcua@0.2.57
#RUN npm install node-red-contrib-s7comm
#RUN npm install npm install node-red-contrib-s7
#RUN npm install node-red-contrib-modbus


COPY /data/settings.js /data/settings.js
COPY /data/flows_cred.json /data/flows_cred.json
COPY /data/flows.json /data/flows.json
