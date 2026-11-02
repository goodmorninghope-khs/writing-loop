# 경로표: 글 종류별 담당 스킬과 게이트

게이트 약어: **평가문체** = 평가로 느껴지지 않는 문체(policy-media-desk references/style-and-selection.md A) · **씨날** = 씨줄(AX2030 5대 전략) × 날줄(민선9기 공약 7대 비전) 교차점 꼬리표 · **사해의** = 사실·해석·의견 구분 · **보도10** = 보도자료 변환 규칙 10(policy-media-desk references/briefing-twin.md) · **선거법** = 공직선거법 제86조 제5항 점검(같은 파일 '법·제도').

| 글 종류 | ① 설계 | ② 초안 | ③ 윤문 | 켤 게이트 | ⑥ 전달·다음 고리 |
|-|-|-|-|-|-|
| 기획안·보고서·제안서·계획서 (내부) | doc-coauthoring | doc-coauthoring | humanize-korean (genre report) | 평가문체(부서·직원 대상일 때), 사해의 | docx 또는 google-docs. 정책화 고리(아궁이·AX2030)로 넘길 거리 제안 |
| 칼럼·창간사·특집·발행인 글 | doc-coauthoring | doc-coauthoring | humanize-korean (column) | 평가문체, 씨날, 사해의 | 채팅 마크다운 또는 google-docs. 정책미디어 지면 후보 |
| 정책미디어 지면 (편집국 글) | - | - | - | **점검만**: 평가문체, 씨날, 사해의, 헌장 3분 읽기 | 점검 메일 문체로 보고. 고쳐 쓰지 않음 |
| 보도자료 → 브리핑 기사 | 원문 1건을 근거 목록으로 | policy-media-desk briefing-twin 기사 템플릿 | humanize-korean (report, light 우선) | 보도10, 사해의, 선거법 | 중랑브리핑 운영 절차로 |
| 보도자료 작성 (구청 발표용) | doc-coauthoring | marketingskills public-relations | humanize-korean (report) | 보도10의 1·2·3·5번을 거꾸로 적용(사실만, 자평 수식어 없이), 선거법 | docx 또는 메일 초안(draft-preview) |
| 인사말씀·축사 | doc-coauthoring(행사 주제·청중) | doc-coauthoring | humanize-korean (essay) | 평가문체, 사실 확인(인용 사례 원문) | 채팅 또는 docx. 인사말씀 저장소(Insamal-Claude-, 포크)는 연계 '제안' 단계 |
| 홍보 문구·슬로건·포스터·랜딩 | marketingskills copywriting | marketingskills copywriting | humanize-korean (blog) | 선거법(주민 배포 시), 과장·검증 안 된 주장 금지 | copy-editing Seven Sweeps 결과를 같이 보고 |
| SNS 게시물·쇼츠 대본 | marketingskills social | marketingskills social | humanize-korean (blog, light) | 선거법(기관 계정), 평가문체 | draft-preview 게시물 카드 |
| 뉴스레터·이메일 캠페인 | marketingskills emails | marketingskills emails | humanize-korean (blog) | 선거법(주민 대상) | draft-preview 메일 카드 |
| 행사 안내·모집 공고 | marketingskills events | marketingskills events | humanize-korean (report, light) | 날짜·장소·신청 방법 사실 게이트 | draft-preview 또는 docx |
| 업무 메일·메시지 | (생략) | 직접 | humanize-korean light | 평가문체(직원에게 보낼 때) | draft-preview |
| AX교실 안내·미션 문구 | ax-classroom-builder 원칙 | ax-classroom-builder | humanize-korean light | 전 직원 대상 쉬운 말, 결과물 중심 | 템플릿 반영 시 ax-classroom-builder '변경은 언제나 스킬까지' |
| AX일지 재료·보고 메일 | ax100-log-desk 형식 | ax100-log-desk 형식 | 하지 않음(형식 보존) | 사해의, 날짜 필수, 개인정보·[비공개] 제외 | ax100-log-desk 메일 절차 |
| 영어 글 | doc-coauthoring | doc-coauthoring 또는 marketingskills | stop-slop | 사해의 | 형식에 맞게 |

genre 값은 humanize-korean shim의 `--genre`(essay·column·report·blog·abstract)다.
