# 설치 및 실행 방법
## 1. 저장소 클론

터미널에서 다음 명령을 실행하여 저장소를 클론합니다. ( 아니면 zip 파일로도 가능 이렇게 했다면 2번으로 넘어가기)
클론 하시고 cd로 프로젝트 폴더 들어가셔서 의존성 설치 하셔야 합니다.

```bash
git clone <https://github.com/hojoon123/next-js-landing.git>
cd <프로젝트 폴더>
```

<br>
<br>

## 2. 의존성 설치

필요한 모든 패키지를 설치합니다.

```bash
npm install
```

위 명령은 `package.json`에 명시된 모든 의존성을 설치합니다. 주요 패키지는 다음과 같습니다:
- next
- react
- react-dom
- lucide-react
- swiper
  
<br>
<br>

## 3. 개발 서버 실행

다음 명령을 실행하여 개발 서버를 시작합니다.

```bash
npm run dev
```

터미널에 표시된 URL (http://localhost:3000/testpage) 로 브라우저를 열면 애플리케이션을 확인할 수 있습니다.

<br>
<br>

## 추가 정보

**프로젝트 구조**:  
소스 코드는 Next.js App Router 구조를 따르며, 페이지 컴포넌트는 `app` 폴더 아래에 위치합니다.
**정적 자산**:  
이미지 및 기타 정적 파일은 `public/assets` 폴더에 위치합니다.

<br>
<br>


## 요약
- 파일 다운로드 -> npm install -> npm run dev -> http://localhost:3000/testpage 확인
- https://claude.ai/ or https://v0.dev/ 등으로 사용하는 프로젝트 기준으로 리팩토링 진행
