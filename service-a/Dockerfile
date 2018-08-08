FROM mhart/alpine-node
EXPOSE 82

WORKDIR /app
COPY package.json .
RUN npm install
COPY . .

CMD ["node", "server.js"2
