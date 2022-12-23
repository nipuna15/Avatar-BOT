FROM quay.io/sampandey001/Avatar
RUN git clone https://github.com/SamPandey001/Avatar-Md /root/SamPandey001
WORKDIR /root/SamPandey001/
RUN npm install npm@latest
RUN yarn install --network-concurrency 1
EXPOSE 8000
CMD ["npm", "start"]
