FROM quay.io/PasiduLk/samuz
RUN git clone https://github.com/PasiduLk/samuza /root/PasiduLk
WORKDIR /root/SamPandey001/
RUN npm install npm@latest
RUN yarn install --network-concurrency 1
EXPOSE 8000
CMD ["npm", "start"]
