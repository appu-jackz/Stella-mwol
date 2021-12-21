FROM souravkl11/raganork:test

RUN git clone https://github.com/appu-jackz/Stella-mwol/ /skl/raganork
WORKDIR /skl/raganork 
ENV TZ = Asia/Kolkata
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "raganork.js"]
