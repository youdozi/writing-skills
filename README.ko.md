# Writing Skills

[English](README.md) | **한국어**

자연스럽고 간결한 글을 쓰고 다듬기 위한 AI 스킬 8개입니다. 한국어를 기본으로 하며 요청한 언어·독자·장르에 맞춰 작성·번역합니다.

## 포함된 스킬

| 스킬 | 용도 |
| --- | --- |
| [writing](skills/writing/SKILL.md) | 교양·시사·커뮤니티·일상·소설·고객 커뮤니케이션 |
| [tech-blog-writing](skills/tech-blog-writing/SKILL.md) | 기술 해설·튜토리얼·트러블슈팅·비교·회고 |
| [translate](skills/translate/SKILL.md) | 의미를 보존한 번역·현지화·번역문 검토 |
| [website-copywriting](skills/website-copywriting/SKILL.md) | 홈페이지·랜딩페이지·서비스 소개·FAQ |
| [cms-ux-writing](skills/cms-ux-writing/SKILL.md) | 관리자 화면의 버튼·도움말·오류·작업 상태 문구 |
| [marketing-pr-writing](skills/marketing-pr-writing/SKILL.md) | 캠페인·광고·SNS·보도자료·공식 입장문 |
| [ai-guide-writing](skills/ai-guide-writing/SKILL.md) | AI 도구 사용법·프롬프트·업무 가이드 |
| [screenplay-writing](skills/screenplay-writing/SKILL.md) | 영화·드라마·숏폼의 시나리오·장면·대사 |

스킬 지침 본문은 현재 주로 한국어로 작성되어 있습니다. 영어 README는 사용 안내이며, 스킬 본문 전체의 영문 번역은 아닙니다.

각 폴더의 `SKILL.md`가 시작점이며, 필요한 세부 지침은 해당 `references/`에서 읽습니다. 모든 참고 문서를 매번 읽거나 모든 작업에 긴 양식을 적용하지 않습니다.

## 설치와 사용

1. 이 저장소를 내려받습니다.
2. 필요한 `skills/<이름>` 폴더를 사용 환경의 스킬 디렉터리에 복사합니다. 기존에 같은 이름의 폴더가 있다면 먼저 차이를 확인하고 보관한 뒤 반영하세요.
3. 새 세션에서 스킬이 발견되는지 확인하고 요청합니다.

Codex 사용자 설치 예시는 `~/.agents/skills/writing/SKILL.md` 형태입니다. 모든 호스트가 이 경로나 호출 표기를 지원하는 것은 아니므로 사용 중인 환경의 설치 방식을 확인하세요. [공식 OpenAI 문서](https://learn.chatgpt.com/docs/build-skills)에서 Codex의 스킬 설치·호출 방법을 확인할 수 있습니다.

요청 예시:

```text
$writing 비 오는 저녁의 편의점을 배경으로 200자 안팎의 짧은 일상 글을 써줘. 가상 장면이고 담백한 말투로 부탁해.

$tech-blog-writing 이 오류 재현 기록으로 기술 글을 써줘. 확인한 원인과 추정을 구분하고 해결·검증 과정을 짧게 정리해줘.

$translate 이 안내를 일본어로 자연스럽게 옮겨줘. 수치·조건과 {version}은 그대로 유지해줘.

$website-copywriting 제공한 서비스 사실만 사용해서 첫 화면 제목·설명·문의 버튼 문구를 만들어줘.
```

## 작성 원칙

- 사실 기반 자료와 허구를 구분하고, 없는 경험·수치·출처를 만들어내지 않습니다.
- 독자의 목적과 화자의 목소리를 유지하며 반복과 상투적인 표현을 줄입니다.
- 번역은 의미·조건·식별자를 보존하면서 독자의 언어·문화 맥락에 맞춥니다.
- 필요한 범위만 검토하고, 실제 확인한 근거와 미확인 사항을 구분합니다.

이 스킬은 에이전트의 작업 지침입니다. 특정 모델·언어·독자·주제의 품질이나 사실 정확성을 보증하지 않으며, 게시 전 사용자의 검토가 필요합니다. 외부 자료를 확인하는 기능은 사용 환경의 도구와 권한에 따라 달라집니다.

## 업데이트

공개 대상 파일을 선별하는 동기화 절차로 관리합니다. 스킬과 이 안내의 변경은 관리 원본에 반영한 뒤 게시하므로, 공개 저장소에 직접 수정한 내용은 다음 동기화에서 덮어써질 수 있습니다.

## 라이선스

[MIT License](LICENSE). 원문에 링크된 외부 문서·기사 등의 권리는 해당 권리자에게 있으며, 이 프로젝트의 라이선스가 그 자료까지 재허락하는 것은 아닙니다.
