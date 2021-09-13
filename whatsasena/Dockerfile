FROM fusuf/whatsasena:latest

RUN git clone https://github.com/Tornymark/Whatsdevil /root/Whatsdevil
WORKDIR /root/Whatsdevil/ 
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit


CMD ["node", "bot.js"]
