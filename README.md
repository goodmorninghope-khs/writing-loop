# writing-loop · 글쓰기 루프

> 접수 → 설계 → 초안 → 윤문 → 점검 → 판정(되돌리기) → 넘기기. 좋은 글은 한 번에 쓰는 게 아니라 고리를 돌며 다듬는다.

여러 글쓰기 스킬을 한 사슬로 엮어 한 편의 글을 완성하는 상위 스킬이다. 각 단계는 이미 있는 스킬이 맡고, 이 스킬은 **순서 · 점검 기준 · 되돌리기 · 기록**만 정한다. Aside에서 쓰도록 만들었지만 SKILL.md 형식이라 다른 에이전트에도 옮길 수 있다.

```
⓪ 접수 → ① 설계 → ② 초안 → ③ 윤문 → ④ 점검 → ⑤ 판정 ─ 통과 → ⑥ 넘기기·기록
                     ▲         ▲         ▲                  │
                     └─────────┴─────────┴──── 미달(최대 3바퀴)
```

## 단계와 담당 스킬

| 단계 | 담당 | 원본 |
|-|-|-|
| ① 설계 · ② 초안(문서) · ④ 독자 시험 | doc-coauthoring | [anthropics/skills](https://github.com/anthropics/skills/tree/main/skills/doc-coauthoring) |
| ② 초안(홍보·카피·SNS·이메일·보도·행사) · ④ Seven Sweeps | marketingskills | [coreyhaines31/marketingskills](https://github.com/coreyhaines31/marketingskills) (MIT) |
| ③ 윤문(한국어) · ④ 변경률 게이트 | humanize-korean | [epoko77-ai/im-not-ai](https://github.com/epoko77-ai/im-not-ai) (MIT) |
| ③ 윤문(영어) · ④ 문체 5축 50점 | stop-slop | [hardikpandya/stop-slop](https://github.com/hardikpandya/stop-slop) (MIT) |
| ④ 기관 게이트(평가로 느껴지지 않는 문체, 씨줄×날줄, 사실·해석·의견, 보도자료 변환 규칙 10, 공직선거법 제86조 제5항) | policy-media-desk | [goodmorninghope-khs/policy-media-desk](https://github.com/goodmorninghope-khs/policy-media-desk) |
| 일지 재료(사실·해석 구분, 날짜) | ax100-log-desk | [goodmorninghope-khs/ax100-log-desk](https://github.com/goodmorninghope-khs/ax100-log-desk) |
| 교육 안내 문구 | ax-classroom-builder | [goodmorninghope-khs/ax-classroom-eogedoene](https://github.com/goodmorninghope-khs/ax-classroom-eogedoene) |

통과 기준: **사실 게이트 · 기관 게이트 통과 + 문체 5축 40/50 이상 + 독자 질문에 막힘 없음**. 미달이면 원인 단계로 되돌린다. 기관 게이트 실패(평가 말투 등)는 문장 틀을 바꾸는 일이라 ③ 윤문이 아니라 ② 초안으로 되돌리고, 윤문 변경률 게이트는 그 회차 초안을 기준선으로 잰다(시험: 원문 대비 74.8% 중단 → 회차 초안 대비 5.5% 통과).

## 구성

| 경로 | 내용 |
|-|-|
| `SKILL.md` | 루프 7단계, 판정·되돌리기 표, 판단 경계, 변경 이력 |
| `references/routes.md` | 글 종류 14가지별 담당 스킬과 켤 게이트 |
| `references/scorecard.md` | 회차별 점검표(A 사실 · B 문체 5축 · C 목적 · D 기관 게이트) |
| `references/lessons.md` | 루프를 돌며 쌓는 노하우 |

## 설치 (Aside)

1. 위 표의 스킬을 Aside 계정 스킬 폴더(`skills/user/`)에 먼저 설치한다. 외부 스킬 셋은 원본 그대로 두고 머리말과 Aside 실행 메모만 덧붙였다.
2. 이 저장소를 `skills/user/writing-loop/`에 넣는다.
3. "글쓰기 루프로 이 보고서 완성해줘", "이 글 점검만 해줘"처럼 부른다.

## 연계 (밸류체인)

| 고리 | 받는 것 | 넘기는 것 | 상태 |
|-|-|-|-|
| ② 제작 | policy-media-desk의 문체·촉 고르기 기준, 보도자료 변환 규칙, 선거법 점검 → 기관 게이트 | 발행인 글(창간사·특집·인사말)의 완성본과 점검표. 편집국 지면은 점검 보고만 | 제안 |
| ② 제작 | im-not-ai(포크)의 한국어 윤문 | 회차별 점수·고친 곳 요지 | 제안 |
| ② 제작 | storytelling-loop의 기획의도·시놉시스·공모전 문서·홍보 문장 | 이야기 글(드라마·시나리오·영상 서사·실화 각색) → [storytelling-loop](https://github.com/goodmorninghope-khs/storytelling-loop) | 연계 |
| ④ 정책화 | - | 완성된 기획안·보고서 → 아궁이·AX2030 항해지도(출처·닿는 공약 붙여 제안) | 제안 |
| ⑥ 기록 | - | 루프 노하우(lessons.md) → 다른 스킬의 문체 기준 보완 | 연계 |

## 원칙

- 사실은 근거 목록(원문)에서만 쓴다. 없는 숫자는 "[확인 필요]"로 남긴다.
- 편집국 지면과 공개 일지는 고쳐 쓰지 않고 점검만 한다. 보내기·게시는 사람이 확인한 뒤에 한다.
- 법률 판단은 하지 않고 "선관위 질의 필요" 같은 확인 거리만 올린다.
- 실제 내부 문서·주민 정보·작업 ID는 이 저장소에 넣지 않는다.
