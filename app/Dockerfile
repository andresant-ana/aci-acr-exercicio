FROM node:current-alpine
WORKDIR /app
COPY . .
RUN npm install --production
EXPOSE 80
CMD ["node", "index.js"]
