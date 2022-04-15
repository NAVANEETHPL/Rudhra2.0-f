FROM fusuf/whatsasena:latest

RUN git clone https://github.com/NAVANEETHPL/Rudhra2.0-f /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Asia/Kolkata
RUN npm install supervisor -g
RUN yarn install --ignore-engines
RUN git clone https://github.com/NAVANEETHPL/files

CMD ["node", "bot.js"]
