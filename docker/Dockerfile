FROM node:alpine

WORKDIR /root/
COPY ./ /root/

RUN npm install @qiita/qiita-cli --save-dev \
	&& npm install @qiita/qiita-cli@latest \
	&& npx qiita init