FROM fusuf/whatsasena:latest

RUN git clone https://github.com/farookser-v1/JEWEL-MOWL /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit
RUN git clone https://github.com/amal-dx/DXTROX

CMD ["node", "bot.js"]
