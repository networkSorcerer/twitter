# Firebase를 활용한 SNS 웹 개발


![img](https://github.com/networkSorcerer/twitter/assets/155520035/f4ef049b-1a63-4adc-bcc1-bd3a85429597)
![images](https://github.com/networkSorcerer/twitter/assets/155520035/b450ad8a-c53c-4d34-922b-ef64e112fb97)

## 소개

이 프로젝트는 Firebase를 사용하여 간단한 SNS(Social Networking Service) 웹 애플리케이션을 개발한 것입니다. 사용자는 회원가입을 통해 계정을 만들고, 다른 사용자들과 글을 공유하며 소통할 수 있습니다.

## 기능

- 사용자 등록 및 인증 (Firebase Authentication)
- 글 작성, 편집, 삭제
- 사용자 간 팔로우 기능
- 실시간 채팅 기능

## 사용 기술

- HTML, CSS, JavaScript (Frontend)
- Firebase (Backend)
  - Firebase Authentication: 사용자 인증 및 권한 관리
  - Cloud Firestore: 데이터베이스로 사용자 정보 및 게시글 저장
  - Firebase Storage: 이미지 및 파일 저장소로 사용
  - Firebase Realtime Database: 실시간 채팅 구현
  - Firebase Hosting: 웹 애플리케이션 호스팅

## 설치 및 실행

1. 이 저장소를 클론합니다.

```bash
git clone https://github.com/your-username/firebase-sns.git
```

2. Firebase 프로젝트를 만들고 설정합니다.
   - Firebase 콘솔에서 새 프로젝트를 만듭니다.
   - Firebase Authentication을 설정하고 이메일/비밀번호 로그인을 활성화합니다.
   - Firestore 데이터베이스를 생성하고 규칙을 설정합니다.
   - Firebase Storage를 설정합니다.

3. Firebase CLI를 설치합니다.

```bash
npm install -g firebase-tools
```

4. 프로젝트 디렉토리로 이동하고 Firebase에 로그인합니다.

```bash
cd firebase-sns
firebase login
```

5. Firebase 프로젝트와 연결합니다.

```bash
firebase use --add
```

6. 프로젝트를 빌드하고 Firebase에 배포합니다.

```bash
firebase deploy
```

7. 웹 애플리케이션을 확인합니다.

```bash
firebase open hosting:site
```

## 기여

이 프로젝트는 여러분의 기여를 환영합니다! 버그 보고, 기능 제안, 코드 개선 등 모든 종류의 기여를 기다립니다. 기여하려면 새로운 브랜치를 만들고 Pull Request를 제출해주세요.

## 라이센스

이 소프트웨어는 MIT 라이센스에 따라 배포됩니다. 자세한 내용은 [LICENSE](LICENSE) 파일을 참조하세요.
