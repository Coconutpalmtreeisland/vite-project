# vite를 이용한 포트폴리오 사이트 만들기

## vite를 사용하는 이유

Vite는 JavaScript 프로젝트를 개발할 때 선택할 수 있는 빌드 도구 중 하나로, 빠른 개발 및 최신 웹 개발 기술을 활용할 수 있는 강력한 도구로서 웹 애플리케이션 및 웹사이트 개발자들에게 유용합니다.

1.빠른 개발 환경: Vite는 개발 서버가 빠르게 동작하며, 빠른 빌드 시간을 제공합니다. 코드 변경 사항을 빠르게 반영하여 개발자가 빠르게 피드백을 받을 수 있습니다.

2.모듈화: Vite는 ES 모듈을 기반으로 하며, 브라우저에서 모듈 로딩을 최적화합니다. 이로써 브라우저에서 필요한 모듈만 로드되므로 초기 페이지 로드 속도가 빨라집니다.

3.다양한 프레임워크 지원: Vite는 Vue.js, React, Svelte 등 다양한 프레임워크와 라이브러리를 지원하며, 개발자들이 선호하는 기술 스택을 사용할 수 있습니다.

4.미들웨어: Vite는 미들웨어를 통해 커스터마이징이 가능하며, 다양한 플러그인을 통해 프로젝트에 기능을 추가하기 쉽습니다.

5.최신 기술 지원: Vite는 최신 JavaScript 및 CSS 표준을 지원하며, 모던 웹 개발에 필요한 도구와 기능을 제공합니다.

[vite](https://ko.vitejs.dev/guide/)

## 구현 기능
- 구글 폰트 적용
- smooth 효과 적용 https://lenis.studiofreight.com/
- 자바스크립트 메뉴 클릭 이동 효과 적용
- GSAP를 이용한 가로 효과
- JavaScript 모듈 기능 적용
- 웹표준 준수를 위한 스킵 메뉴 및 aira, role 적용
- vite 빌드 작업 `npm run build`
- netilfy 배포 작업

## 트러블 슈팅-에러 해결 방법
<details>
    <summary>
        error: remote origin already exists.
        The requested URL returned error: 403
    </summary>

    자격 증명 관리자 > Windows 자격 증명 > 일반 자격 증명에 있는 GitHub를 수정하면 로그인 후에

    echo "# vite-project" >> README.md
    >> git init
    >> git add README.md
    >> git commit -m "first commit"
    >> git remote add origin https://github.com/Coconutpalmtreeisland/vite-project.git

    하면 저장소가 재연결되어 업로드 됩니다.

</details>

## module

협업 시 구조화하고 한줄 작업(용량 줄이기)을 하기 위해(번들링) 사용합니다.
원조는 웹팩이며 vite에서 사용 가능합니다.
