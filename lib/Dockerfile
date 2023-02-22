FROM fusuf/whatsasena:latest

RUN https://github.com/Gabrieljerad/zimbot-v4

WORKDIR /Drips/Zimbotv4

ENV TZ=Africa/Nairobi

RUN npm install

RUN npm install supervisor -g
RUN yarn install --ignore-engines
CMD ["node", "index.js"]
