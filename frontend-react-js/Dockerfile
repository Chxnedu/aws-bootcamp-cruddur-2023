FROM node:16.18 AS installer
COPY . /frontend-react-js
WORKDIR /frontend-react-js
RUN npm install

FROM node:16.18-alpine3.17
ENV PORT=3000
WORKDIR /frontend-react-js
COPY --from=installer /frontend-react-js /frontend-react-js/
EXPOSE ${PORT}
CMD ["npm", "start"]