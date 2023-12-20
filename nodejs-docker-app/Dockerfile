# 베이스 이미지를 명시
FROM node:10

# 워크 디렉토리 설정
WORKDIR /usr/src/app

# 종속성 관련
COPY package.json ./

# 추가적으로 필요한 파일들을 다운로드 받는다.
RUN npm install

COPY ./ ./

# 컨테이너 시작 시 실행 될 명령어를 명시해준다.
CMD ["node", "server.js"]