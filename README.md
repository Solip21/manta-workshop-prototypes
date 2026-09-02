# Manta Workshop Prototypes

AI 워크샵에서 만든 클릭 가능한 프로토타입을 아카이브하고 재사용하기 위한 저장소입니다.

## 구조

워크샵(또는 기능)마다 하나의 폴더로 관리합니다.

```
/<날짜 또는 기능명>
  README.md      # 무엇을 만들었는지, 어떤 One Pager·PRD와 연결되는지
  (프로토타입 코드)
```

## 컨벤션

- 웹 기반(React/HTML)으로 만들어 설치 없이 링크 하나로 볼 수 있게 한다.
- 저장소 전체가 Vercel 프로젝트 하나(`manta-workshop-prototypes`)에 연결되어 있다. 폴더별로 `https://manta-workshop-prototypes.vercel.app/<폴더명>/` 경로로 바로 접근할 수 있다. 관련 Notion 문서에 이 링크를 남긴다.
- 다음 워크샵에서 비슷한 화면이 필요하면 기존 폴더를 참고하거나 복사해서 시작한다.

## 주제 트래킹

프로토타입 주제·작업자·공유 날짜는 Notion [프로젝트 아카이브](https://app.notion.com/p/ridi/3a52d79d7707800f9a92edb9653c7f6e?v=3a52d79d77078067a39d000c545e91ee) 데이터베이스에서 계속 업데이트된다. 새 폴더를 추가할 때 이 목록도 함께 갱신한다.

## 프로토타입 목록

| 폴더 | 배포 링크 | 워크샵 | 관련 문서 |
|---|---|---|---|
| [`poll`](./poll) | [바로가기](https://manta-workshop-prototypes.vercel.app/poll/) | Episode Interpretation Poll | [Poll One Pager](https://app.notion.com/p/ridi/One-Pager-3b12d79d7707809db6f2cbc896032d11) |
| [`content-ownership`](./content-ownership) | [바로가기](https://manta-workshop-prototypes.vercel.app/content-ownership/) | 콘텐츠 소장감 강화 | [상세 스펙](https://app.notion.com/p/3c22d79d7707806ab82dfa13615f5495) |

> Context Badge, Effects Test/Haptic Feedback 시나리오는 이 저장소가 아니라 다른 프로젝트라서 [manta-prototypes](https://github.com/Solip21/manta-prototypes), [interaction-test](https://github.com/Solip21/interaction-test) 저장소로 옮겼습니다.
