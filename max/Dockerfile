FROM fusuf/whatsasena:latest

RUN git clone https://github.com/bharathapriyanath/max /root/max
WORKDIR /root/max/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
