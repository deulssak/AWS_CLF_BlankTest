# AWS CLF-C02 비공식 학습 앱
### Unofficial Study App for AWS Certified Cloud Practitioner (CLF-C02)

> ⚠️ **비공식 학습 도구입니다 / Unofficial study tool**
> This project is not affiliated with or endorsed by AWS.
> AWS, Amazon Web Services and related marks are trademarks of Amazon.com, Inc.

---

## 소개 / About

AWS Certified Cloud Practitioner(CLF-C02) 시험 준비를 위해 직접 만든 비공식 학습 앱입니다.
빈칸채우기와 시나리오 객관식 두 가지 모드로 핵심 개념을 반복 학습할 수 있습니다.
이 앱은 클로드를 사용해 작성되었습니다

An unofficial self-study app built for AWS CLF-C02 exam prep.
Covers fill-in-the-blank and scenario-based multiple choice across all 4 exam domains.
This app write by Cloude.ai.

---

## 기능 / Features

- 📝 **빈칸채우기 200문제** — 서비스명·개념어 암기용
- 🎯 **시나리오 객관식 80문제** — 실전 감각 훈련용
- 🇰🇷🇺🇸 **한국어·영어 정답 동시 인정** — 어느 쪽으로 입력해도 정답 처리
- 📊 **도메인별 필터** — 도메인 1·2·3 개별 학습 가능
- ❌ **오답 필터** — 틀린 문제만 모아서 반복 학습
- 📈 **실시간 정답률 + 회독 수 표시**
- 📱 **모바일 최적화** — 안드로이드·iOS 브라우저에서 바로 사용 가능
- 🌐 **오프라인 사용 가능** — 단일 HTML 파일로 인터넷 없이도 작동

---

## 시험 도메인 구성 / Exam Domains

| 도메인 | 내용 | 가중치 |
|--------|------|--------|
| 도메인 1 | 클라우드 개념 | 24% |
| 도메인 2 | 보안 및 규정 준수 | 30% |
| 도메인 3 | 클라우드 기술 및 서비스 | 34% |
| 도메인 4 | 결제, 요금 및 지원 | 12% |

> 합격 기준: 1000점 만점 중 700점 이상 / Passing score: 700/1000

---

## 사용 방법 / How to Use

### 브라우저에서 바로 사용 (GitHub Pages)
아래 링크에서 바로 실행할 수 있습니다.

🔗 **[빈칸채우기 앱 열기](https://deulssak.github.io/AWS_CLF_BlankTest/clf_blank.html)**
🔗 **[객관식 앱 열기](https://deulssak.github.io/AWS_CLF_BlankTest/clf_quiz.html)**

### 로컬에서 사용
```bash
git clone https://github.com/[username]/[repo-name].git
# clf_blank.html 또는 clf_quiz.html을 브라우저로 열기
```

### 안드로이드에서 앱처럼 사용
1. 크롬에서 위 링크 접속
2. 우측 상단 메뉴 → **홈 화면에 추가**
3. 홈 화면 아이콘으로 앱처럼 실행

---

## 파일 구조 / File Structure

```
├── index.html          # 메인 랜딩 페이지
├── clf_blank.html      # 빈칸채우기 앱 (200문제)
├── clf_quiz.html       # 시나리오 객관식 앱 (80문제)
└── README.md
```

---

## 학습 권장 순서 / Recommended Study Order

```
1단계  도메인 3 빈칸채우기  →  도메인 3 객관식
2단계  도메인 2 빈칸채우기  →  도메인 2 객관식
3단계  도메인 1 빈칸채우기  →  도메인 1 객관식
4단계  전체 오답 필터로 반복
5단계  정답률 80% 이상 유지되면 시험 등록
```

---

## 기여 / Contributing

오타 수정, 문제 추가, 번역 개선 등 PR 환영합니다.
Pull requests are welcome — typo fixes, new questions, translation improvements.

---

## 면책 조항 / Disclaimer

- 이 프로젝트는 AWS와 무관한 개인 학습 목적의 비공식 도구입니다.
- 문제는 AWS 공식 시험 안내서의 공개된 내용을 바탕으로 자체 제작되었습니다.
- 실제 시험 문제와 다를 수 있으며, 합격을 보장하지 않습니다.

This is an unofficial personal study tool, not affiliated with Amazon Web Services.
Questions are independently created based on the publicly available CLF-C02 exam guide.
Actual exam questions may differ.

---

## 라이선스 / License

MIT License — 자유롭게 사용, 수정, 배포 가능합니다.

---

<div align="center">
  Made with ☕ while studying for AWS CLF-C02<br>
  <sub>도쿄에서 클라우드 아키텍트를 꿈꾸며 만들었습니다</sub>
</div>
