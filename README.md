# Next.js Todo App - Render 배포 실습

Next.js + MongoDB (Mongoose)를 사용한 투두 리스트 애플리케이션입니다. Render 클라우드 플랫폼에 배포하고 GitHub Actions를 통한 CI/CD를 구성하는 실습 프로젝트입니다.

## 🚀 기능

- ✅ 투두 추가, 조회, 수정, 삭제 (CRUD)
- ✅ 완료/미완료 상태 토글
- ✅ MongoDB를 통한 데이터 영구 저장
- ✅ Tailwind CSS로 구성된 모던한 UI
- ✅ GitHub Actions를 통한 자동 배포 (CI/CD)

## 📋 사전 요구사항

- Node.js 18 이상
- MongoDB Atlas 계정 (또는 로컬 MongoDB)
- GitHub 계정
- Render 계정

## 🛠️ 로컬 개발 환경 설정

### 1. 프로젝트 클론 및 의존성 설치

```bash
# 의존성 설치
npm install
```

### 2. 환경 변수 설정

`.env.local` 파일을 생성하고 MongoDB 연결 문자열을 입력하세요:

```env
MONGODB_URI=mongodb+srv://<username>:<password>@<cluster>.mongodb.net/?retryWrites=true&w=majority
```

### 3. MongoDB Atlas 설정

1. [MongoDB Atlas](https://www.mongodb.com/cloud/atlas)에 가입
2. 무료 클러스터 생성
3. Database Access에서 사용자 생성
4. Network Access에서 IP 주소 추가 (로컬 개발 시 `0.0.0.0/0` 허용 가능)
5. Connect → Drivers에서 연결 문자열 복사

### 4. 개발 서버 실행

```bash
npm run dev
```

브라우저에서 [http://localhost:3000](http://localhost:3000)을 열어 확인하세요.


## 📄 라이선스

이 프로젝트는 교육 목적으로 제작되었습니다.
