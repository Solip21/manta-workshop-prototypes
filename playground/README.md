# Playground — Episode Interpretation Poll

Design팀 AI 워크샵 프로젝트. Xcode 프로젝트 `Playground`(로컬: `~/Developer/Playground`)의 Episode Interpretation Poll 시나리오를 웹으로 그대로 옮긴 클릭 가능한 프로토타입입니다. 설치 없이 링크 하나로 팀원이 iOS Safari를 포함한 아무 브라우저에서 탭해볼 수 있습니다.

**Episode Interpretation Poll** — 회차 뷰어 인라인 폴, 투표 시 실시간 득표율 갱신, "Ask Readers"로 직접 질문·선택지 작성, 회차 이미지에서 하이라이트 구간 드래그로 선택, 내가 만든 폴 수정/삭제

- One Pager: https://app.notion.com/p/ridi/One-Pager-3b12d79d7707809db6f2cbc896032d11
- Highlight 첨부 스펙: https://app.notion.com/p/3b12d79d770780f38578ef1fad489719
- Figma: https://www.figma.com/design/JrWrOZSh2Xx2JWt45LllbZ/-Task--%EC%86%94%EC%9E%8E?node-id=752-28894

Context Badge, Effects Test/Haptic Feedback 시나리오는 다른 프로젝트라서 각각 [manta-prototypes](https://github.com/Solip21/manta-prototypes), [interaction-test](https://github.com/Solip21/interaction-test) 저장소로 분리했습니다.

## 구조

`index.html` 하나로 완결된 정적 페이지입니다 (별도 빌드 스텝 없음). Manta 다크 토큰 색상, Poppins 폰트, Xcode 프로젝트의 실제 회차 이미지를 전부 인라인(base64)으로 내장하고 있어 외부 리소스 없이 그대로 열립니다.

## 업데이트 방법

Xcode `Playground` 프로젝트에서 이 시나리오가 바뀌면 이 폴더의 `index.html`을 다시 생성해서 교체하고 Vercel에 재배포합니다.

## 배포

https://manta-workshop-prototypes.vercel.app/playground/
