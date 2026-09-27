# goorm-260927-claude-proj

여러 개별 프로젝트를 `projects/` 하위에 폴더 단위로 모아두는 모노레포입니다. 프로젝트마다 별도의 폴더와 README를 가지며, 이 루트 README는 전체 프로젝트 목록을 안내하는 인덱스 역할만 합니다.

## 폴더 구조

```
.
├── README.md                 # 이 파일 — 전체 프로젝트 인덱스
└── projects/
    └── nordvik-discount-calculator/
        ├── README.md          # 프로젝트별 설명
        └── nordvik-discount-calculator.html
```

새 프로젝트는 `projects/<project-slug>/` 형태로 폴더를 추가합니다. 프로젝트 간 코드나 의존성을 공유하지 않는 한, 폴더 내부 구성은 프로젝트마다 자유롭게 구성해도 됩니다.

## 프로젝트 목록

| 프로젝트 | 설명 | 경로 |
|---|---|---|
| Nordvik 할인 수익성 계산기 | BCR 영업마케팅팀이 Nordvik Automation 견적 할인 요청의 주문 수익성을 검토하는 내부용 웹 계산기 | [`projects/nordvik-discount-calculator/`](projects/nordvik-discount-calculator/) |

> 앞으로 추가될 프로젝트는 이 표에 한 줄씩 추가해 주세요.

## 새 프로젝트 추가 방법

1. `projects/<project-slug>/` 폴더를 생성합니다. (예: `projects/bcr-quote-approval/`)
2. 해당 폴더 안에 프로젝트 전용 `README.md`를 작성합니다 — 목적, 주요 기능, 사용 방법, 기술 스택, 주의 사항을 포함합니다.
3. 프로젝트 소스/자산 파일을 같은 폴더 안에 둡니다.
4. 이 루트 `README.md`의 "프로젝트 목록" 표에 새 행을 추가합니다.
