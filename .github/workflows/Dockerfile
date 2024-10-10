FROM node:20.18.0

WORKDIR /workspace
COPY . .

RUN yarn install --frozen-lockfile
RUN cd ./packages/jaeger-ui && yarn build
