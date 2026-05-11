# AI 자동화 컨설팅 제안서 디자인 초안

이 문서는 AI 자동화 컨설팅 제안서 PPT를 만들 때 참고할 디자인 초안입니다. 특정 브랜드의 공식 디자인 시스템이 아니며, 이번 한글 제안서 작업을 빠르고 일관되게 진행하기 위한 안내입니다.

## Overview

이 제안서의 디자인은 두 가지 성격을 함께 가집니다.

첫째, 앞부분은 발표용 자료처럼 넓고 인상적으로 보이게 만듭니다. 표지, 문제 제기, 핵심 제안 페이지에는 부드러운 그라데이션 배경과 큰 제목을 사용해 전문적이고 현대적인 느낌을 줍니다.

둘째, 중간과 뒷부분은 정보가 많은 실무 문서처럼 정리합니다. 자동화 대상 업무, 실행 일정, 비용, 기대 효과, 리스크 관리 같은 내용은 표, 카드, 3열 구성, 체크리스트를 사용해 빠르게 비교하고 이해할 수 있게 만듭니다.

강조색은 민트 계열의 초록색을 적게 쓰되, 중요한 행동 버튼, 확인 표시, 선택된 상태, 긍정적인 효과에만 사용합니다. 기본 행동 버튼은 검정색 알약 모양으로 쓰고, 어두운 배경에서는 흰색 알약 버튼을 사용합니다.

본문과 제목은 읽기 쉬운 산세리프 글꼴을 사용합니다. 자동화 흐름, 시스템 이름, 변수명, 예시 프롬프트처럼 기술적인 느낌이 필요한 부분에는 고정폭 글꼴을 제한적으로 사용합니다.

**Key Characteristics:**

* 부드러운 하늘색, 크림색, 짙은 청록색 그라데이션을 사용한 영화 같은 첫인상
* 민트 초록색은 핵심 CTA, 선택 상태, 성공 표시, 중요한 확인 포인트에만 사용
* 검정색 알약 버튼을 기본 CTA로 사용
* 어두운 배경에서는 흰색 알약 버튼으로 반전 처리
* 본문과 제목은 Inter 또는 비슷한 산세리프 글꼴 사용
* 자동화 규칙, 프롬프트, 시스템 예시는 Geist Mono 또는 비슷한 고정폭 글꼴 사용
* 제안서 본문은 14–16px 기준으로 촘촘하지만 읽기 편하게 구성
* 카드 모서리는 12px 중심으로 통일하고, 버튼은 완전히 둥근 알약 모양으로 통일
* 따뜻한 오렌지 계열 카드는 고객 후기, 핵심 인용, 감정적인 설득 포인트에만 사용

## Colors

### Accent

* **Accent Mint** (`{colors.accent-mint}`): 가장 중요한 강조색입니다. 시작하기 버튼, 체크 아이콘, 선택된 카드 테두리, 활성 상태 표시 등에 사용합니다.
* **Deep Mint** (`{colors.accent-mint-deep}`): 민트 버튼을 눌렀거나 더 강하게 보이고 싶을 때 사용합니다.
* **Soft Mint** (`{colors.accent-mint-soft}`): 성공 메시지, 작은 확인 영역, 긍정적인 배경 강조에 사용합니다.
* **Reference Blue** (`{colors.reference-blue}`): 문서 안의 참고 태그, 시스템 이름, 링크형 칩에 사용합니다.
* **Annotation Green** (`{colors.annotation-green}`): 자동화 예시, 프롬프트 설명, 코드 주석처럼 보조 설명이 필요한 곳에 사용합니다.
* **Warning Amber** (`{colors.warning-amber}`): 주의, 확인 필요, 리스크 설명에 사용합니다.
* **Error Red** (`{colors.error-red}`): 필수 입력, 오류, 보안 위험, 금지 항목에 사용합니다.
* **Warm Orange** (`{colors.warm-orange}`): 고객 인용, 변화 전후 스토리, 강한 메시지를 담은 카드에 제한적으로 사용합니다.

### Surface

* **Canvas White** (`{colors.canvas}`): 기본 슬라이드와 카드 배경입니다.
* **Canvas Dark** (`{colors.canvas-dark}`): 어두운 히어로 영역, 강조 배너, 자동화 예시 화면 배경에 사용합니다.
* **Surface** (`{colors.surface}`): 연한 회색 배경, 검색창 모양, 칩, 선택된 사이드 항목에 사용합니다.
* **Surface Soft** (`{colors.surface-soft}`): 더 조용한 섹션 배경, FAQ, 보조 설명 영역에 사용합니다.
* **Surface Code** (`{colors.surface-code}`): 코드 블록, 프롬프트 예시, 자동화 규칙 예시를 담는 어두운 박스에 사용합니다.
* **Hairline** (`{colors.hairline}`): 1px 테두리와 기본 구분선에 사용합니다.
* **Hairline Soft** (`{colors.hairline-soft}`): 표 행 구분선, 덜 중요한 섹션 구분선에 사용합니다.

### Hero Atmospheric

* **Hero Sky From / To** (`{colors.hero-sky-from}`, `{colors.hero-sky-to}`): 표지나 첫 제안 페이지에 쓰는 하늘색에서 부드러운 크림색으로 이어지는 그라데이션입니다.
* **Hero Dark From / To** (`{colors.hero-dark-from}`, `{colors.hero-dark-to}`): 강한 메시지를 전할 때 쓰는 짙은 청록색에서 민트색으로 이어지는 그라데이션입니다.

### Text

* **Ink** (`{colors.ink}`): 제목과 가장 중요한 문장에 사용합니다.
* **Charcoal** (`{colors.charcoal}`): 일반 본문에 사용합니다.
* **Slate** (`{colors.slate}`): 보조 설명, 메타 정보, 작은 안내 문구에 사용합니다.
* **Steel** (`{colors.steel}`): 표 머리글, 비활성 항목, 덜 중요한 링크 느낌의 텍스트에 사용합니다.
* **Stone** (`{colors.stone}`): 캡션, 작은 라벨, 부가 설명에 사용합니다.
* **Muted** (`{colors.muted}`): 비활성 또는 아직 확정되지 않은 항목에 사용합니다.
* **On Dark** (`{colors.on-dark}`): 어두운 배경 위의 흰색 텍스트입니다.
* **On Dark Muted** (`{colors.on-dark-muted}`): 어두운 배경 위에서 덜 강조되는 흰색 텍스트입니다.

### Semantic

* 오류와 위험 표시는 `{colors.error-red}`를 기준으로 합니다.
* 주의와 검토 필요 표시는 `{colors.warning-amber}`를 기준으로 합니다.
* 성공과 확정 표시는 `{colors.accent-mint}` 또는 `{colors.accent-mint-soft}`를 기준으로 합니다.

## Typography

### Font Family

**Inter** 또는 비슷한 산세리프 글꼴을 기본 글꼴로 사용합니다. 제목, 본문, 버튼, 캡션, 표 안의 글자까지 대부분의 텍스트에 사용합니다. 대체 글꼴은 `-apple-system`, `BlinkMacSystemFont`, `Segoe UI`, `sans-serif`를 권장합니다.

**Geist Mono** 또는 비슷한 고정폭 글꼴은 제한적으로 사용합니다. 예를 들어 자동화 규칙, 프롬프트 예시, 시스템 필드명, 데이터 항목, 코드처럼 보이는 내용에 사용합니다. 대체 글꼴은 `SF Mono`, `Menlo`, `Consolas`, `monospace`를 권장합니다.

기울임 글꼴은 되도록 사용하지 않습니다. 강조가 필요할 때는 굵기, 색상, 배경 칩, 밑줄을 사용합니다.

### Hierarchy

| Token | Size | Weight | Line Height | Letter Spacing | Use |
| --- | --- | --- | --- | --- | --- |
| `{typography.hero-display}` | 72px | 600 | 1.05 | -2px | 표지의 큰 제목 |
| `{typography.display-lg}` | 56px | 600 | 1.10 | -1.5px | 주요 섹션 시작 제목 |
| `{typography.heading-1}` | 48px | 600 | 1.10 | -1px | 페이지 수준의 핵심 제목 |
| `{typography.heading-2}` | 36px | 600 | 1.20 | -0.5px | 섹션 제목 |
| `{typography.heading-3}` | 28px | 600 | 1.25 | 0 | 소제목, 큰 카드 제목 |
| `{typography.heading-4}` | 22px | 600 | 1.30 | 0 | 일반 카드 제목 |
| `{typography.heading-5}` | 18px | 600 | 1.40 | 0 | 작은 카드 제목, FAQ 질문 |
| `{typography.subtitle}` | 18px | 400 | 1.50 | 0 | 표지 부제목, 리드 문장 |
| `{typography.body-md}` | 16px | 400 | 1.50 | 0 | 기본 본문 |
| `{typography.body-md-medium}` | 16px | 500 | 1.50 | 0 | 본문 안의 강조 |
| `{typography.body-sm}` | 14px | 400 | 1.50 | 0 | 표, 보조 본문, 카드 설명 |
| `{typography.body-sm-medium}` | 14px | 500 | 1.50 | 0 | 버튼, 탭, 활성 항목 |
| `{typography.caption}` | 13px | 400 | 1.40 | 0 | 도움말, 작은 안내, 코드 블록 제목 |
| `{typography.caption-bold}` | 13px | 600 | 1.40 | 0 | 배지 라벨 |
| `{typography.micro}` | 12px | 500 | 1.40 | 0 | 아주 작은 설명, 하단 메모 |
| `{typography.micro-uppercase}` | 11px | 600 | 1.40 | 0.5px | 섹션 라벨, 필수 표시 |
| `{typography.button-md}` | 14px | 500 | 1.30 | 0 | 알약 버튼 텍스트 |
| `{typography.code-md}` | 14px | 400 | 1.50 | 0 | 코드 또는 프롬프트 블록 |
| `{typography.code-sm}` | 13px | 400 | 1.40 | 0 | 작은 코드, 필드 타입 |
| `{typography.code-inline}` | 13px | 500 | 1.30 | 0 | 본문 안의 짧은 코드형 표현 |

### Principles

* 큰 제목은 줄 간격을 좁게 잡아 힘 있게 보이게 합니다.
* 큰 글자일수록 글자 간격을 조금 줄여 더 정돈되어 보이게 합니다.
* 본문은 1.50 줄 간격을 유지해 오래 읽어도 편하게 만듭니다.
* 산세리프 글꼴은 설명과 발표용 문장에 사용합니다.
* 고정폭 글꼴은 자동화 흐름, 프롬프트, 데이터 필드처럼 기술적 느낌이 필요한 곳에만 사용합니다.
* 대문자 라벨은 섹션 구분, 필수 표시, 상태 표시처럼 짧은 곳에만 사용합니다.

## Layout

### Spacing System

* **Base unit**: 4px입니다. 실제 배치는 8px 단위로 맞추면 편합니다.
* **Tokens**: `{spacing.xxs}` 4px · `{spacing.xs}` 8px · `{spacing.sm}` 12px · `{spacing.md}` 16px · `{spacing.lg}` 20px · `{spacing.xl}` 24px · `{spacing.xxl}` 32px · `{spacing.xxxl}` 40px · `{spacing.section-sm}` 48px · `{spacing.section}` 64px · `{spacing.section-lg}` 96px · `{spacing.hero}` 120px
* **Section rhythm**: 표지와 큰 메시지 페이지는 96–120px 정도의 넓은 여백을 사용합니다. 표, 일정, 비용 페이지는 32–64px 정도로 더 촘촘하게 구성합니다.
* **Card internal padding**: 일반 카드는 24px, 중요한 카드나 가격/일정 카드는 32px, 큰 인용 카드는 64px까지 사용할 수 있습니다.

### Grid & Container

* 와이드 슬라이드는 16:9 비율을 기본으로 생각합니다.
* 한 페이지의 안전 여백은 좌우 48–64px 정도로 둡니다.
* 표지와 핵심 제안 페이지는 가운데 정렬 또는 2열 구성을 사용합니다.
* 문제와 해결책 비교 페이지는 2열 구성이 좋습니다.
* 서비스 패키지나 실행 단계는 3열 카드 구성이 좋습니다.
* 상세 내용 페이지는 왼쪽 요약, 가운데 본문, 오른쪽 체크리스트의 3열 구성을 사용할 수 있습니다.
* 표가 긴 경우에는 제목과 핵심 수치가 먼저 보이게 하고, 세부 항목은 작은 글자로 정리합니다.

### Whitespace Philosophy

앞부분의 발표용 페이지는 여백을 크게 사용합니다. 그래야 그라데이션 배경과 큰 제목이 잘 보입니다.

뒤쪽의 실무 설명 페이지는 더 촘촘하게 구성합니다. 단, 줄 간격과 카드 안쪽 여백은 줄이지 않습니다. 정보가 많아도 답답하지 않게 보이려면 여백을 완전히 없애지 않는 것이 중요합니다.

## Elevation & Depth

전체적으로는 평평한 디자인을 기본으로 합니다. 그림자와 깊이감은 정말 중요한 화면 예시나 핵심 카드에만 사용합니다.

| Level | Treatment | Use |
| --- | --- | --- |
| 0 flat | 그림자 없음, `{colors.hairline}` 1px 테두리 | 기본 카드, 표, 입력 박스 |
| 1 subtle | `rgba(0, 0, 0, 0.04) 0px 1px 2px 0px` | 살짝 떠 보이는 보조 카드 |
| 2 card | `rgba(0, 0, 0, 0.08) 0px 4px 12px 0px` | 주요 기능 카드 |
| 3 mockup | `rgba(0, 0, 0, 0.12) 0px 24px 48px -8px` | 자동화 대시보드나 화면 예시 |
| 4 accent-tinted | `rgba(0, 212, 164, 0.08) 0px 8px 24px` | 선택된 패키지, 추천안 강조 |

### Decorative Depth

* 표지에는 부드러운 그라데이션과 추상적인 구름형 배경을 사용해 깊이감을 줍니다.
* 강한 제안 메시지 페이지에는 어두운 청록색 계열 그라데이션을 사용합니다.
* 코드나 프롬프트 예시 박스는 어두운 배경과 색상 대비로 깊이감을 줍니다.
* 모든 카드에 강한 그림자를 넣지 않습니다. 중요한 카드만 선택적으로 띄웁니다.

## Shapes

### Border Radius Scale

| Token | Value | Use |
| --- | --- | --- |
| `{rounded.xs}` | 4px | 인라인 코드 칩, 작은 태그 |
| `{rounded.sm}` | 6px | 작은 상태 배지, 작은 메뉴형 항목 |
| `{rounded.md}` | 8px | 입력 박스, 검색 박스, 코드 블록, 작은 카드 |
| `{rounded.lg}` | 12px | 일반 카드, 가격 카드, FAQ, 화면 예시 |
| `{rounded.xl}` | 16px | 큰 기능 패널 |
| `{rounded.xxl}` | 24px | 특별한 쇼케이스 카드 |
| `{rounded.full}` | 9999px | 모든 버튼, 알약 탭, 배지 |

모서리 값은 일관되게 사용합니다. 버튼은 항상 완전히 둥근 알약 모양으로 만들고, 일반 카드는 12px을 기본으로 합니다.

### Image Geometry

* 히어로 배경 이미지는 전체 영역을 채우고, 내부 프레임은 최소화합니다.
* 화면 예시 이미지는 12px 둥근 모서리와 얇은 테두리를 사용합니다.
* 인물 사진이 필요한 경우 1:1 비율과 8px 둥근 모서리를 사용합니다.
* 추상 일러스트는 메시지를 방해하지 않도록 투명도와 대비를 낮춥니다.

## Components

아래 컴포넌트 이름은 PPT를 만들 때 반복해서 쓸 수 있는 구성 요소 이름입니다. 실제 도구에서 반드시 같은 이름을 쓸 필요는 없습니다.

### Buttons

**`button-primary`** — 밝은 배경에서 쓰는 기본 검정색 알약 버튼입니다.

* 배경 `{colors.primary}`, 텍스트 `{colors.on-primary}`, 글자 `{typography.button-md}`, 패딩 `10px 20px`, 모서리 `{rounded.full}`.
* 눌린 상태는 `{colors.charcoal}`로 조금 밝게 보이게 합니다.
* 비활성 상태는 `{colors.hairline}` 배경과 `{colors.muted}` 텍스트를 사용합니다.

**`button-accent-mint`** — 가장 중요한 강조 행동에 쓰는 민트색 알약 버튼입니다.

* 배경 `{colors.accent-mint}`, 텍스트 `{colors.primary}`, 글자 `{typography.button-md}`, 패딩 `10px 20px`, 모서리 `{rounded.full}`.

**`button-on-dark`** — 어두운 배경 위에 쓰는 흰색 알약 버튼입니다.

* 배경 `{colors.on-dark}`, 텍스트 `{colors.primary}`, 글자 `{typography.button-md}`, 패딩 `10px 20px`, 모서리 `{rounded.full}`.

**`button-secondary`** — 두 번째 행동에 쓰는 외곽선 알약 버튼입니다.

* 배경 투명, 텍스트 `{colors.ink}`, 테두리 `1px solid {colors.hairline}`, 글자 `{typography.button-md}`, 패딩 `10px 20px`, 모서리 `{rounded.full}`.

**`button-ghost`** — 덜 중요한 행동에 쓰는 조용한 버튼입니다.

* 배경 투명, 텍스트 `{colors.ink}`, 글자 `{typography.button-md}`, 패딩 `8px 12px`, 모서리 `{rounded.md}`.

**`button-link`** — 문장 안에서 링크처럼 쓰는 버튼입니다.

* 배경 투명, 텍스트 `{colors.ink}`, 글자 `{typography.body-sm-medium}`, 패딩 `0`.

**`button-icon-circular`** — 복사, 닫기, 다음 이동 같은 작은 아이콘 버튼입니다.

* 크기 32×32px, 배경 `{colors.canvas}`, 텍스트 `{colors.ink}`, 테두리 `1px solid {colors.hairline}`, 모서리 `{rounded.full}`.

### Cards & Containers

**`card-base`** — 기본 설명 카드입니다.

* 배경 `{colors.canvas}`, 모서리 `{rounded.lg}`, 패딩 `{spacing.xl}`, 테두리 `1px solid {colors.hairline}`.

**`card-feature`** — 기능 또는 기대 효과를 설명하는 카드입니다.

* 배경 `{colors.surface}`, 모서리 `{rounded.lg}`, 패딩 `{spacing.xxl}`.

**`card-help`** — 다음 단계, 상담 요청, 자료 요청 같은 안내 카드입니다.

* 배경 `{colors.canvas}`, 모서리 `{rounded.lg}`, 패딩 `{spacing.xl}`, 테두리 `1px solid {colors.hairline}`.

**`card-automation-perk`** — 자동화 도입 효과를 보여주는 그리드 카드입니다.

* 배경 `{colors.canvas}`, 모서리 `{rounded.lg}`, 패딩 `{spacing.xl}`, 테두리 `1px solid {colors.hairline}`.
* 상단에는 단순한 아이콘, 중간에는 `{typography.heading-5}` 제목, 하단에는 `{typography.body-sm}` 설명을 둡니다.

**`proposal-package-card`** — 제안 패키지 또는 단계별 서비스 카드입니다.

* 배경 `{colors.canvas}`, 모서리 `{rounded.lg}`, 패딩 `{spacing.xxl}`, 테두리 `1px solid {colors.hairline}`.
* 제목은 `{typography.heading-3}`, 핵심 금액 또는 기간은 `{typography.display-lg}`, 포함 항목은 `{typography.body-sm}`와 민트 체크 아이콘으로 구성합니다.

**`proposal-package-featured`** — 추천 패키지 또는 우선 실행안을 강조하는 카드입니다.

* 배경 `{colors.canvas}`, 모서리 `{rounded.lg}`, 패딩 `{spacing.xxl}`, 테두리 `2px solid {colors.accent-mint}`, 그림자 `rgba(0, 212, 164, 0.08) 0px 8px 24px`.

**`testimonial-card-feature`** — 고객 인용이나 강한 메시지를 담는 따뜻한 오렌지 카드입니다.

* 배경 `{colors.warm-orange}`, 텍스트 `{colors.on-dark}`, 모서리 `{rounded.lg}`, 패딩 `{spacing.section}`.
* 왼쪽에는 큰 인용문을 `{typography.heading-3}`로 넣고, 아래에는 출처나 상황 설명을 `{typography.body-sm-medium}`으로 넣습니다.

**`testimonial-card-quote`** — 작은 흰색 인용 카드입니다.

* 배경 `{colors.canvas}`, 모서리 `{rounded.lg}`, 패딩 `{spacing.xxl}`, 테두리 `1px solid {colors.hairline}`.

**`program-card`** — 진단, 설계, 파일럿, 확산 단계를 담는 큰 카드입니다.

* 배경 `{colors.canvas}`, 모서리 `{rounded.lg}`, 패딩 `{spacing.xxl}`, 테두리 `1px solid {colors.hairline}`.

### Inputs & Forms

**`text-input`** — 워크숍 입력 예시나 질문지 화면을 표현할 때 쓰는 입력 박스입니다.

* 배경 `{colors.canvas}`, 텍스트 `{colors.ink}`, 테두리 `1px solid {colors.hairline}`, 모서리 `{rounded.md}`, 패딩 `{spacing.sm} {spacing.md}`, 높이 40px.

**`text-input-focused`** — 선택된 입력 박스입니다.

* 테두리를 `2px solid {colors.accent-mint}`로 바꿔 현재 입력 중임을 보여줍니다.

**`search-pill`** — 자료 검색, 업무 검색, 자동화 항목 검색을 보여줄 때 쓰는 검색 박스입니다.

* 배경 `{colors.surface}`, 텍스트 `{colors.steel}`, 글자 `{typography.body-sm}`, 모서리 `{rounded.md}`, 높이 36px, 테두리 `1px solid {colors.hairline}`.

### Tabs

**`segmented-tab`** + **`segmented-tab-active`** — 여러 관점을 나눠 보여주는 밑줄형 탭입니다.

* 비활성: 텍스트 `{colors.steel}`, 배경 투명, 패딩 `{spacing.sm} {spacing.md}`.
* 활성: 텍스트 `{colors.ink}`, 아래쪽 2px 선 `{colors.ink}`.

**`pill-tab`** + **`pill-tab-active`** — 제안 범위, 월간/연간, 기본/확장 같은 선택지를 보여주는 알약형 탭입니다.

* 비활성: 배경 `{colors.canvas}`, 텍스트 `{colors.steel}`, 테두리 `1px solid {colors.hairline}`, 패딩 `8px 16px`, 모서리 `{rounded.full}`.
* 활성: 배경 `{colors.primary}`, 텍스트 `{colors.on-primary}`, 테두리 없음.

**`toggle-two-state`** — 두 가지 선택지를 보여주는 토글입니다.

* 배경 `{colors.surface}`, 모서리 `{rounded.full}`, 패딩 `4px`.
* 활성 상태는 흰색 알약이 선택된 쪽으로 이동한 것처럼 표현합니다.

### Badges & Status

**`badge-saving`** — 시간 절감, 비용 절감 같은 긍정 결과 배지입니다.

* 배경 `{colors.accent-mint}`, 텍스트 `{colors.primary}`, 글자 `{typography.caption-bold}`, 모서리 `{rounded.full}`, 패딩 `2px 8px`.

**`badge-required`** — 필수 확인 항목 배지입니다.

* 배경 `{colors.error-red}`, 텍스트 `{colors.on-dark}`, 글자 `{typography.micro-uppercase}`, 모서리 `{rounded.sm}`, 패딩 `2px 6px`.

**`badge-type`** — 데이터 종류나 업무 유형을 표시하는 배지입니다.

* 배경 `{colors.surface}`, 텍스트 `{colors.steel}`, 글자 `{typography.code-sm}`, 모서리 `{rounded.sm}`, 패딩 `2px 6px`.

**`badge-tag`** — 참고 항목, 자동화 단계, 관련 도구를 표시하는 태그입니다.

* 배경 `rgba(55, 114, 207, 0.15)`, 텍스트 `{colors.reference-blue}`, 글자 `{typography.caption-bold}`, 모서리 `{rounded.sm}`, 패딩 `2px 8px`.

**`promo-banner`** — 아주 중요한 한 줄 메시지 배너입니다.

* 배경 `{colors.canvas-dark}`, 텍스트 `{colors.on-dark}`, 글자 `{typography.body-sm-medium}`, 패딩 `{spacing.sm} {spacing.md}`.

### Code & Automation Examples

**`code-block`** — 프롬프트, 자동화 규칙, 데이터 처리 예시를 담는 어두운 박스입니다.

* 배경 `{colors.surface-code}`, 텍스트 `{colors.on-dark}`, 글자 `{typography.code-md}`, 모서리 `{rounded.md}`, 패딩 `{spacing.md}`.

**`code-block-header`** — 코드 박스 위쪽의 작은 제목 영역입니다.

* 배경 `{colors.surface-code}`, 텍스트 `{colors.on-dark-muted}`, 글자 `{typography.caption}`, 패딩 `{spacing.xs} {spacing.md}`, 아래쪽 테두리 `1px solid {colors.hairline-dark}`.

**`code-inline`** — 본문 안의 짧은 시스템명, 필드명, 프롬프트 키워드입니다.

* 배경 `{colors.surface}`, 텍스트 `{colors.charcoal}`, 글자 `{typography.code-inline}`, 모서리 `{rounded.xs}`, 패딩 `2px 6px`, 테두리 `1px solid {colors.hairline}`.

**`copy-code-button`** — 예시 내용을 복사하는 작은 버튼 표현입니다.

* 배경 투명, 텍스트 `{colors.on-dark-muted}`, 글자 `{typography.caption}`, 모서리 `{rounded.sm}`, 패딩 `{spacing.xxs} {spacing.xs}`, 테두리 `1px solid {colors.hairline-dark}`.

### Proposal Detail Components

**`property-row`** — 자동화 대상 업무나 데이터 항목을 한 줄씩 설명하는 행입니다.

* 배경 투명, 텍스트 `{colors.ink}`, 글자 `{typography.body-sm}`, 패딩 `{spacing.md} 0`, 아래쪽 테두리 `1px solid {colors.hairline-soft}`.
* 왼쪽에는 항목명, 가운데에는 유형 배지, 오른쪽에는 설명을 둡니다.

**`feature-comparison-table`** — 패키지별 기능 비교표입니다.

* 배경 `{colors.canvas}`, 텍스트 `{colors.ink}`, 글자 `{typography.body-sm}`, 모서리 `{rounded.md}`, 테두리 `1px solid {colors.hairline}`.

**`feature-comparison-row`** — 비교표 안의 개별 행입니다.

* 배경 `{colors.canvas}`, 텍스트 `{colors.ink}`, 패딩 `{spacing.md} {spacing.lg}`, 아래쪽 테두리 `1px solid {colors.hairline-soft}`.
* 섹션 구분 행은 `{typography.micro-uppercase}`와 `{colors.steel}`을 사용합니다.

**`side-summary-item`** + **`side-summary-item-active`** — 슬라이드 안의 왼쪽 요약 목록입니다.

* 비활성: 배경 투명, 텍스트 `{colors.steel}`, 글자 `{typography.body-sm}`, 모서리 `{rounded.sm}`, 패딩 `{spacing.xs} {spacing.md}`.
* 활성: 배경 `{colors.surface}`, 텍스트 `{colors.ink}`, 글자 `{typography.body-sm-medium}`.

**`section-label`** — 작은 섹션 제목입니다.

* 배경 투명, 텍스트 `{colors.steel}`, 글자 `{typography.micro-uppercase}`, 패딩 `{spacing.md} {spacing.md} {spacing.xs}`.

**`toc-item`** + **`toc-item-active`** — 긴 제안서에서 현재 위치를 보여주는 목차 항목입니다.

* 비활성: 배경 투명, 텍스트 `{colors.steel}`, 글자 `{typography.body-sm}`, 패딩 `{spacing.xxs} 0`.
* 활성: 텍스트 `{colors.ink}`, 글자 `{typography.body-sm-medium}`, 선택적으로 왼쪽에 `{colors.accent-mint}` 선을 둡니다.

### Signature Components

**`hero-band-sky`** — 표지 또는 첫 제안 페이지에 쓰는 밝은 히어로 영역입니다.

* 배경은 `linear-gradient(180deg, {colors.hero-sky-from} 0%, {colors.hero-sky-to} 100%)`를 사용합니다.
* 제목은 가운데에 `{typography.hero-display}`로 배치합니다.
* 부제목은 `{typography.subtitle}`로 제목 아래에 둡니다.
* 버튼 행은 `button-accent-mint`와 `button-secondary` 조합을 사용합니다.
* 아래쪽에는 자동화 대시보드나 업무 흐름 예시 목업을 배치할 수 있습니다.

**`hero-band-dark`** — 강한 메시지나 전환점 페이지에 쓰는 어두운 히어로 영역입니다.

* 배경은 `linear-gradient(135deg, {colors.hero-dark-from} 0%, {colors.hero-dark-to} 100%)`를 사용합니다.
* 텍스트는 `{colors.on-dark}`를 사용합니다.
* 왼쪽에는 큰 제목, 오른쪽에는 추상적인 자동화 흐름 일러스트를 배치합니다.
* 버튼은 `button-on-dark`와 조용한 보조 링크를 조합합니다.

**`hero-product-mockup`** — 자동화 화면 예시나 대시보드 목업입니다.

* 배경 `{colors.canvas}`, 모서리 `{rounded.lg}`, 테두리 `1px solid {colors.hairline-soft}`, 그림자 `rgba(0, 0, 0, 0.12) 0px 24px 48px -8px`.
* 내부에는 왼쪽 메뉴, 가운데 본문, 오른쪽 체크리스트 같은 화면 구조를 넣을 수 있습니다.

**`trust-row-item`** — 신뢰 근거를 나열하는 셀입니다.

* 배경 투명, 텍스트 `{colors.steel}`, 글자 `{typography.body-md-medium}`, 패딩 `{spacing.lg}`.
* 고객 수, 처리 시간, 자동화 건수, 파일럿 기간 같은 짧은 지표를 넣습니다.

**`faq-accordion-item`** — 자주 묻는 질문 카드입니다.

* 배경 `{colors.canvas}`, 모서리 `{rounded.md}`, 패딩 `{spacing.xl}`, 테두리 `1px solid {colors.hairline-soft}`.
* 질문은 `{typography.heading-5}`, 답변은 `{typography.body-md}`와 `{colors.steel}`을 사용합니다.

**`closing-region`** — 마지막 페이지 또는 다음 단계 안내 영역입니다.

* 배경 `{colors.canvas}`, 위쪽 테두리 `1px solid {colors.hairline}`, 패딩 `{spacing.section} {spacing.xxl}`.
* 다음 행동, 준비물, 연락 방식, 예상 일정을 2–3열로 정리합니다.

**`closing-link`** — 마지막 페이지의 보조 안내 항목입니다.

* 배경 투명, 텍스트 `{colors.steel}`, 글자 `{typography.body-sm}`, 패딩 `{spacing.xxs} 0`.

## Do's and Don'ts

### Do

* `{colors.accent-mint}`는 중요한 CTA, 활성 상태, 성공 표시처럼 의미가 분명한 곳에만 사용합니다.
* 밝은 배경에서는 검정색 `button-primary`를 기본 행동 버튼으로 사용합니다.
* 어두운 배경에서는 흰색 `button-on-dark`를 사용합니다.
* 모든 버튼과 알약형 탭은 `{rounded.full}`을 사용합니다.
* 본문은 산세리프 글꼴, 코드형 예시는 고정폭 글꼴로 나눠 사용합니다.
* 그라데이션 히어로는 표지와 주요 전환 페이지에만 사용합니다.
* 일반 카드는 `{rounded.lg}` 12px을 기본으로 사용합니다.
* 긴 본문은 `{typography.body-md}` 16px과 1.50 줄 간격을 유지합니다.
* 정보가 많은 페이지는 표, 카드, 체크리스트로 나눠서 보여줍니다.

### Don't

* `{colors.accent-mint}`를 본문 전체나 큰 배경에 넓게 사용하지 않습니다.
* 민트, 파랑, 빨강, 오렌지 외에 새로운 강조색을 계속 추가하지 않습니다.
* 모든 카드에 무거운 그림자를 넣지 않습니다.
* 본문 줄 간격을 1.50보다 지나치게 줄이지 않습니다.
* 그라데이션 배경 위에 여러 강조색을 동시에 올리지 않습니다.
* 기술 예시가 아닌 일반 문장에 고정폭 글꼴을 사용하지 않습니다.
* 버튼의 모서리를 중간 정도로만 둥글게 만들지 않습니다. 버튼은 항상 알약 모양입니다.
* 실제로 확정되지 않은 고객 성과를 사실처럼 쓰지 않습니다.

## Responsive Behavior

PPT는 주로 16:9 화면에서 보이지만, PDF나 작은 화면으로 확인할 수 있으므로 축소되었을 때도 읽히게 만듭니다.

### Breakpoints

| Name | Width | Key Changes |
| --- | --- | --- |
| Mobile small | < 480px | 한 열 구성. 히어로 제목은 36px 수준. 표는 카드형으로 바꿉니다. |
| Mobile large | 480–767px | 한 열 또는 2열 카드. 히어로 제목은 44px 수준. |
| Tablet | 768–1023px | 2열 카드와 간단한 표를 사용합니다. 히어로 제목은 56px 수준. |
| Desktop | 1024–1279px | 2–3열 구성, 3개 패키지 카드, 큰 히어로 제목 72px 사용. |
| Wide Desktop | ≥ 1280px | 넓은 여백, 큰 목업, 더 안정적인 3열 정보 배치 사용. |

### Touch Targets

* 알약 버튼은 기본 높이 36–40px로 만들고, 작은 화면에서는 44px 이상으로 키웁니다.
* 원형 아이콘 버튼은 데스크톱 32×32px, 모바일 44×44px을 권장합니다.
* 입력 박스는 기본 40px, 모바일 44px 높이를 권장합니다.
* 목록형 항목은 모바일에서 44px 정도의 높이를 확보합니다.

### Collapsing Strategy

* 상단의 긴 문장은 작은 화면에서 줄이거나 두 줄로 나눕니다.
* 2열 히어로는 작은 화면에서 위아래로 쌓습니다.
* 3열 카드 구성은 태블릿에서 2열, 모바일에서 1열로 바꿉니다.
* 긴 비교표는 모바일에서 가로 스크롤 또는 카드형 목록으로 바꿉니다.
* 히어로 제목은 72px → 56px → 44px → 36px 순서로 줄입니다.
* 신뢰 지표 행은 6개 → 3개 → 2개 → 1개 순서로 줄입니다.

### Image Behavior

* 추상 일러스트는 SVG처럼 선명한 형식을 우선합니다.
* 화면 목업은 비율을 유지하며 줄어들게 합니다.
* 사진은 너무 어둡거나 복잡하지 않은 이미지를 사용합니다.
* 작은 화면에서는 장식 이미지를 줄이고 핵심 텍스트를 먼저 보이게 합니다.

## Iteration Guide

1. 한 번에 하나의 컴포넌트만 고칩니다.
2. 토큰 이름을 그대로 참고합니다. 예: `{colors.primary}`, `{rounded.full}`, `button-primary`.
3. 색을 추가하기 전에 기존 색으로 해결할 수 있는지 먼저 확인합니다.
4. 새 상태가 필요하면 `-active`, `-pressed`, `-disabled`, `-focused`처럼 이름을 분리합니다.
5. 본문은 기본적으로 `{typography.body-md}`를 사용하고, 강조 문장은 `{typography.subtitle}`를 사용합니다.
6. 제목은 `hero-display → display-lg → heading-1 → heading-2 → heading-3 → heading-4 → heading-5` 순서로 단계적으로 낮춥니다.
7. 민트색이 일반 배경처럼 넓게 쓰였다면 정말 필요한지 다시 확인합니다.
8. 버튼은 항상 `{rounded.full}`을 사용합니다.
9. 긴 설명은 16px, 1.50 줄 간격을 유지합니다.
10. PPT 제작 전에는 표지, 핵심 제안, 실행 일정, 비용, 다음 단계 페이지부터 먼저 시안으로 확인합니다.

## Known Gaps

* 실제 고객 업종, 고객명, 발표 시간에 따라 색과 문장 톤을 조정해야 합니다.
* 구체적인 이미지 자료가 아직 없으므로, 추상 일러스트와 목업 중심으로 시작합니다.
* 애니메이션 속도는 아직 정하지 않았습니다. 필요하면 150–200ms 정도의 짧고 부드러운 전환을 권장합니다.
* 보안, 개인정보, 내부 승인 기준은 고객 상황 확인 후 별도 페이지로 보강해야 합니다.
* 코드나 프롬프트 예시의 색상 규칙은 아직 세부 확정 전입니다. 실제 예시가 정해지면 추가로 다듬습니다.
