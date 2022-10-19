FROM mjgargani/puppeteer:trybe1.0
WORKDIR  /usr/app
EXPOSE 300
ADD node_modules.tar.gz .
COPY . .
CMD ["npm", "test"] 
