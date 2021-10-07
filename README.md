# Node.js(express)

### Middleware

app.use(미들웨어); 와 같은 형태로 사용

- cookie-parser // app.use(cookieParser); // req.cookies... 으로 값 접근 가능
- morgan // 로그 남기기 편한 미들웨어(모니터링) // app.use(morgan('combined')) // combined 말고도 다양하게 있음
- helmet // 보안 관련 헤더 추가

