FROM fusuf/whatsasena:latest

RUN git clone https://github.com/agentmax123/4.0-x /root/4.0-x
WORKDIR /root/4.0-x/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
