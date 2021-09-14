FROM fusuf/whatsasena:latest

RUN git clone https://github.com/agentmax123/4.0_PLUGIN_X /root/4.0_PLUGIN_X
WORKDIR /root/4.0_PLUGIN_X/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
