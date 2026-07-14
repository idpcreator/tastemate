🍽️ Tastemate

팀의 맛집을 함께 발견하고 공유하는 플랫폼입니다. IDP 컨설팅팀 출장 중 만난 식당과 카페를 지도에 기록하세요.

✨ 주요 기능


👤 Google 로그인: 팀원이 개별적으로 로그인하여 기록
📝 식사 경험 기록: 식당/카페명, 주소, 평점, 메모 등 기록
🗺️ 지도 보기: Kakao Map을 통해 모든 기록된 장소를 지도에서 확인
📊 통계: 방문 기록, 평균 평점, 카테고리별 분류 등
🔍 필터링: 지역, 카테고리별로 기록 검색
☁️ 클라우드 동기화: Firebase를 통해 실시간 데이터 공유


🛠️ 기술 스택


Frontend: Next.js 14, React 18, Tailwind CSS
Backend: Firebase (Authentication, Firestore)
Map: Kakao Map API
Deployment: Vercel


📋 설치 및 실행

자세한 설정 가이드는 SETUP_GUIDE.md를 참고하세요.

빠른 시작

bash# 1. 의존성 설치
npm install

# 2. 환경변수 설정
# .env.local 파일 생성 후 필수 API 키 입력

# 3. 로컬 실행
npm run dev

# 4. 브라우저 접속
# http://localhost:3000

🚀 배포

Vercel에 배포하기

bash# 1. GitHub에 푸시
git push origin main

# 2. Vercel 대시보드에서 프로젝트 import
# https://vercel.com

# 3. 환경변수 설정
# Vercel Settings → Environment Variables

# 4. 자동 배포 완료!

배포 후 URL을 팀원들과 공유하세요.

📖 사용 방법


로그인: Google 계정으로 로그인
기록 추가: 좌측 "새로운 기록"에 정보 입력

장소명, 주소, 카테고리(식당/카페)
평점(1-5), 함께한 동료, 메모



기록 확인:

📋 목록 뷰: 모든 기록을 카드 형태로 확인
🗺️ 지도 뷰: 지도에서 위치 확인



필터링: 카테고리, 지역명으로 검색


📊 통계


총 기록 수
평균 평점
식당 / 카페별 분류
방문한 지역 수


🔐 보안


Google OAuth 2.0 인증
Firebase Firestore 보안 규칙 적용
자신이 작성한 기록만 삭제 가능
모든 데이터는 암호화되어 저장됨


🐛 트러블슈팅

문제 발생 시 SETUP_GUIDE.md의 트러블슈팅 섹션을 참고하세요.

📝 라이선스

개인 사용 목적

👥 팀

IDP 컨설팅팀

💬 피드백

기능 개선 사항이나 버그는 팀에 알려주세요!


Tastemate와 함께 팀의 맛집을 발견하세요! 🍽️☕
