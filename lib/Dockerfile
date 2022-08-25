FROM fusuf/whatsasena:latest

RUN git clone 437864b1-f547-4f69-ba2c-923c9bb38682 /Drips/Zimbotv4

WORKDIR /Drips/Zimbotv4

ENV TZ=Africa/Harare

RUN npm install

RUN npm install supervisor -g
RUN yarn install --ignore-engines
CMD ["node", "index.js"]
