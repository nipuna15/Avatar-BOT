FROM quay.io/Avatar_Team/Avatar
RUN git clone https://github.com/nipuna15/Avatar-BOT /root/Avatar_Team
WORKDIR /root/Avatar_Team/
RUN npm install npm@latest
RUN yarn install --network-concurrency 1
EXPOSE 8000
CMD ["npm", "start"]
