FROM node

RUN mkdir -p /app
COPY web /app
COPY 01-tinder-swipe /app
WORKDIR /app
RUN npm install .
EXPOSE 4321
ENTRYPOINT ["npm", "start", "build"]
