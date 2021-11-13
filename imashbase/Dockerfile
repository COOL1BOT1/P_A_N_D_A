FROM fusuf/whatsasena:latest

RUN git clone https://github.com/COOL1BOT1/P_A_N_D_A /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
