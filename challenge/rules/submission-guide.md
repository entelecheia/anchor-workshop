# 제출 가이드

> GitHub을 처음 쓰는 분도 따라할 수 있도록 단계별로 설명합니다.

**제출 마감**: 2026년 5월 22일(목) 23:59

---

## 방법 1: GitHub PR (권장)

GitHub 계정이 없어도 됩니다. 아래 단계를 따라주세요.

### 1단계: GitHub 계정 만들기

1. https://github.com 접속
2. "Sign up" 클릭
3. 이메일(대학 이메일 권장), 사용자명, 비밀번호 설정
4. 이메일 인증 완료

### 2단계: 저장소 Fork

1. https://github.com/[저장소-주소] 접속 (운영팀이 공지)
2. 우측 상단 "Fork" 버튼 클릭
3. 내 계정으로 Fork 완료

### 3단계: 제출 폴더 만들기

1. Fork한 내 저장소에서 `challenge/submissions/` 폴더로 이동
2. "Add file" → "Create new file" 클릭
3. 파일 이름 입력: `팀명/README.md`
   - 예: `team-ai-helper/README.md`
   - 팀명은 영문 소문자, 하이픈 사용 (예: `team-budget-wizard`)
4. `challenge/templates/submission-readme.md` 내용을 복사해서 붙여넣기
5. 내용 채우기 (아래 항목 설명 참조)
6. "Commit changes" 클릭

### 4단계: Pull Request 제출

1. 내 Fork 저장소 상단의 "Contribute" → "Open pull request" 클릭
2. PR 제목: `[카테고리] 팀명 — 작품명`
   - 예: `[A] team-budget-wizard — 예산 집행 자동 분석기`
3. PR 본문: 팀명, 카테고리, 한 줄 설명 작성
4. "Create pull request" 클릭
5. PR URL을 Slack `#anchor-workshop`에 공유

---

## 방법 2: Slack 직접 제출 (GitHub 어려운 경우)

GitHub이 너무 어렵다면 Slack으로 제출해도 됩니다.

1. `challenge/templates/submission-readme.md`를 다운로드하여 작성
2. 추가 파일(프롬프트, 샘플 등)과 함께 압축 (zip)
3. Slack `#anchor-workshop` 채널에 업로드
4. 메시지: `[제출] [카테고리] 팀명 — 작품명`

---

## 제출 폴더 구조

```
challenge/submissions/
└── your-team-name/
    ├── README.md          (필수 — 양식 사용)
    ├── prompts/           (프롬프트 파일들)
    │   └── main-prompt.md
    ├── samples/           (샘플 입출력)
    │   ├── input-sample.md
    │   └── output-sample.md
    └── demo/              (데모 자료, 선택)
        └── demo-notes.md
```

---

## 제출 전 체크리스트

- [ ] 팀명 폴더명이 영문 소문자 + 하이픈
- [ ] README.md 양식 모든 항목 작성
- [ ] 개인정보 없음 (이름, 학번, 급여 등)
- [ ] 성과 수치 포함 (시간 절감 등)
- [ ] 재현 방법 명시
- [ ] PR 제목 형식 준수

---

## 자주 묻는 질문

**Q: GitHub을 전혀 모릅니다.**
A: Slack 직접 제출 방법을 이용하거나, Slack `#anchor-workshop`에 도움 요청하세요. 운영팀이 도와드립니다.

**Q: 혼자 참가해도 되나요?**
A: 네, 개인 참가도 가능합니다. 팀 구성이 어렵다면 운영팀에 문의해 팀 매칭을 요청하세요.

**Q: 제출 후 수정이 가능한가요?**
A: 마감(5/22 23:59) 전까지 수정 가능합니다. PR에 추가 커밋을 올리거나 Slack에 수정본을 공유하세요.

**Q: 어떤 파일 형식으로 제출하나요?**
A: 마크다운(.md), 텍스트(.txt), CSV(.csv)만 허용됩니다. HWP, PDF, 이미지 파일 불필요.
