# 세모하우스 아티클

세모하우스 팀의 아티클을 모아두는 레포입니다.

## 팀

아티클 본문에 매번 쓰지 않는 공통 정보입니다. 아티클에는 내용만 담고,
누가 언제 했는지는 여기를 참고합니다.

| 역할 | 이름 |
| --- | --- |
| PM & Product Designer | Terry |
| Graphic Designer | Daisy |
| Developer | <!-- TODO: 이름 --> |
| Marketers | <!-- TODO: 이름 --> |

## 프로젝트

| 프로젝트 | 기간 | 비고 |
| --- | --- | --- |
| 일본여름카메라 | <!-- TODO: YYYY.MM ~ YYYY.MM --> | iOS 앱 |

## 아티클

| 날짜 | 제목 | 프로젝트 |
| --- | --- | --- |
| 2026-08-19 | [조회수 말고 전환율](articles/2026-08-19-japan-summer-camera-conversion.md) | 일본여름카메라 |

## 구조

```
articles/
├── YYYY-MM-DD-slug.md    아티클 본문
└── images/               본문에 들어가는 이미지
```

## 쓰는 법

Claude Code에서 `/team-article`을 실행하거나 "회고 아티클 초안 써줘"라고
요청하면 팀 템플릿에 맞춘 초안이 `articles/`에 생성됩니다.

템플릿·문체 규칙은 `~/.claude/skills/team-article/`에 있습니다.

- `TEMPLATE.md` — 아티클 골격
- `TONE.md` — 문체와 용어 표기
- `CHECKLIST.md` — 발행 전 점검
- `EXAMPLES/` — 잘 나온 글을 넣어두면 다음 글이 그 문체를 따라갑니다
