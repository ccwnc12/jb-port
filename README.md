# JB-PORT

전북 투자정보사이트 프론트엔드 프로토타입.

## 실행

빌드나 npm 설치 없이 정적 파일 서버로 실행합니다. Mac에 Python 3가 설치되어 있다면 프로젝트 폴더에서:

```sh
python3 -m http.server 8080 --directory dist
```

브라우저에서 http://localhost:8080 을 엽니다.

## 파일

- dist/app.js: 목록, 검색, 로그인 체험, 관리자 기능
- dist/business-config.js: 사업 분야, 투자 단계, 필터 및 샘플 데이터
- dist/company-profile.js: 기업 등록, 상세, Excel 데이터
- dist/form-enhancements.js: 사업장, 날짜, 입력 검증, PDF 저장
- dist/style.css: 스타일
- .openai/hosting.json: 기존 Sites 프로젝트 연결 설정 (인증키 아님)

## 데이터 저장

프론트엔드 프로토타입으로 서버 인증이나 공용 데이터베이스가 없습니다. 기업정보와 계정은 localStorage, 로그인은 sessionStorage, 업로드 PDF는 IndexedDB에 저장됩니다. 다른 컴퓨터로 소스만 복사해도 입력 데이터는 옮겨지지 않습니다. 샘플은 가상 데이터입니다.

## 맥북에서 이어서 작업

GitHub 저장소를 복제하고 Codex에서 해당 폴더를 엽니다. HANDOFF.md를 먼저 읽도록 요청하세요. 이 저장소는 전체 채팅 원문을 포함하지 않습니다.
