FROM quay.io/lyfe00011/test:beta

RUN git clone https://github.com/Krishnadev98/Julie-Mwol /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
RUN yarn install --no-audit
RUN git clone https://github.com/Krishnadev98/Julie-Mwol/media
RUN cp -R /root/Utils/* /root/WhatsAsenaDuplicated 
CMD ["node", "bot.js"]
