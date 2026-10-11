# user-flow-design

모바일 앱·웹의 핵심 업무를 **탐색 → 상세 → 입력 → 상태 전환 → 복귀** 동선으로 설계·구현·검증하는 Claude Code 스킬입니다.
신규 서비스 제작, 기존 UX 개선, 참고 앱의 흐름을 다른 분야에 적용할 때 씁니다.

## 구성
```
SKILL.md                     # 스킬 본문 (작업 범위, 6단계 절차)
references/patterns.md       # 정보 구조·패턴 선택 기준, 다른 분야 매핑 방법
references/verification.md   # 검증 계획·결과 기록 형식, 증거 수준
```

## 설치

**개인용 (모든 프로젝트에서 사용)**
```bash
git clone https://github.com/beryvery/user-flow-design-skill ~/.claude/skills/user-flow-design
```

**프로젝트용 (해당 저장소에서만 사용)**
```bash
git clone https://github.com/beryvery/user-flow-design-skill .claude/skills/user-flow-design
```

설치 후 Claude Code에서 `/user-flow-design` 으로 호출하거나, 앱·웹 화면 흐름을 설계·구현·검증해 달라고 요청하면 자동으로 적용됩니다.

## 사용 예
- "이 예약 서비스의 모바일 앱 동선을 설계해 줘"
- "참고 앱의 탐색 구조를 우리 학습 플랫폼에 맞게 바꿔서 구현해 줘"
- "주문 생성부터 취소까지 주요 경로를 검증하고 보고서를 만들어 줘"

## 라이선스
MIT
