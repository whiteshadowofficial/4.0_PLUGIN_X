FROM fusuf/RAVANA:latest

RUN git clone https://github.com/farhan-dqz/Julie-Mwol /root/4.0
WORKDIR /root/4.0/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
