FROM quay.io/cyberudayipp/zroxy
RUN git clone https://github.com/CYBERUDAYIPP/ZROXY-MD /root/cyberudayipp
https://github.com/CYBERUDAYIPP/ZROXY-MD.git
WORKDIR /root/cyberudayipp/
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]
