# Node.js(express)

### Middleware

app.use(미들웨어); 와 같은 형태로 사용

- cookie-parser // app.use(cookieParser); // req.cookies... 으로 값 접근 가능
- morgan // 로그 남기기 편한 미들웨어(모니터링) // app.use(morgan('combined')) // combined 말고도 다양하게 있음
- helmet // 보안 관련 헤더 추가



### NPM 통한 미들웨어 설치 및 세팅 

 
- npm i express cors cookie-parser morgan helmet express-async-errors 와 같이 한꺼번에 여러 개 설치 가능
- npm i nodemon --save-dev 
- package.json 들어가서 script에 start 추가 및 nodemon 적용(서버 시작 npm start로 가능해짐), main 아래에 type: module 적용
