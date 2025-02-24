## API 명세서(상세기입)

### 📌 [회원 관련 API]
| HTTP Method | URL | 요청 데이터 | 응답 데이터 | 설명 |  
| --- | --- | --- | --- | --- |
| POST | `/auth/signup` | "id": "" / "pw":"" / "name":"" / "gender": "" / "phoneNumber":"", "address" : ""  | "message": "회원가입 성공" | 회원가입 API |
| POST | `/auth/login` | "id": "" / "pw":"" | "message":"로그인 성공" | 로그인 API |
| GET | `/users/me` | "" |  | 내 정보 조회 API |  