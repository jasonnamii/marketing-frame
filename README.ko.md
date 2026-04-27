# marketing-frame-engine

> 🇺🇸 [English README](./README.md)

**마케팅 프레임 라우터 v1.0. 140+ 프레임 × 3축 라우팅(시간·고객·실행) × 2모드(기획·진단) × 듀얼 출력(.md+.html 벤토). 산업별 6프레임 레시피 자동.**

## 사전 요구

- **Claude Cowork 또는 Claude Code** 환경
- 선택: 옵시디언 볼트(.md 마스터 산출물 저장용)

## 목표

마케팅 기획·진단은 종종 "프레임 과부하"에 빠집니다. 4P·STP·AARRR·JTBD·Cynefin·Wardley를 따로 알고 있어도 "지금 이 상황에 어떤 조합이 맞나"를 모릅니다. 본 스킬은 3축(시간·고객 깔때기·실행 페이즈)으로 라우팅한 뒤 140+ 프레임 DB에서 MECE 검증된 3~6개를 선택하고, 산업별 레시피로 10슬롯 벤토 캔버스를 채워 그 문제를 해결합니다.

## 사용 시점 & 방법

마케팅 기획 시작, 정체된 캠페인 진단, 제안서 마케팅 섹션 작성, "이 상황에 어떤 프레임 렌즈로 봐야 하나" 질문이 들 때 발동. **프레임 라우터 전용**으로, 카피·피치덱·재무모델·UI·IMC 실행은 전담 스킬에 위임합니다.

## 사용 사례

| 상황 | 프롬프트 | 동작 |
|---|---|---|
| 시리즈 A 직전 SaaS, 유지율 18% | `"시리즈 A 직전 SaaS 성장 전략 짜줘"` | PLAN 모드 → SaaS B2B 레시피 → Strategy Diamond + AARRR + NSM+Counter + Reverse Trial |
| D2C 뷰티 매출 정체 | `"광고비 늘어도 CAC만 오름. 진단해줘"` | DIAGNOSE 모드 → D2C 레시피 → HEAVY-LIGHT + Four Realms + Cohort + RFM |
| 캠페인 사후 복기 | `"지난 캠페인 벤토로 복기"` | DIAGNOSE → 10슬롯 벤토(.md + .html), backward One Promise |

## 주요 기능

- **140+ 프레임** 6 카테고리: 고전 컨설팅·디지털 그로스·브랜드 크리에이티브·심리·B2B/플랫폼·메타/신흥
- **3축 라우팅**: Cynefin 시간 스코프 × 깔때기 고객 단계 × 실행 페이즈
- **2모드**: PLAN(forward, 가설) vs DIAGNOSE(backward, 근거)
- **산업 레시피**: 8 도메인 × 6 프레임 자동 매칭 (SaaS B2B·D2C·미디어·금융·리테일·스타트업·플랫폼·브랜드 캠페인)
- **벤토 출력**: 10 슬롯 (Strategic Q · Routing · Frames · Pain · AS-IS/TO-BE · Issues · FAQ Gap · Counter-Metric · One Promise · Confidence)
- **듀얼 포맷**: 옵시디언 `.md` 마스터 + 애플 스타일 `.html` 벤토 (A4 인쇄 + 1080p 발표)
- **Counter-Metric 가드**: NSM 단일 지표 과적화 방지

## 연동 스킬

- **[copywriting-engine](https://github.com/jasonnamii/copywriting-engine)** — 프레임 선택 후 카피 생성
- **[bp-guide](https://github.com/jasonnamii/bp-guide)** — 마케팅 전략 후 피치덱
- **[financial-model](https://github.com/jasonnamii/financial-model)** — 프레임 라우팅 후 매출 시나리오
- **[ui-action-designer](https://github.com/jasonnamii/ui-action-designer)** — 카피 후 랜딩 페이지 UI
- **[brand-campaign](https://github.com/jasonnamii/brand-campaign)** — 전략 후 IMC 캠페인 실행
- **[ads-playbook](https://github.com/jasonnamii/ads-playbook)** — 미디어 플랜 후 광고 운영 튜닝

## 설치

```bash
git clone https://github.com/jasonnamii/marketing-frame-engine.git ~/.claude/skills/marketing-frame-engine
```

## 업데이트

```bash
cd ~/.claude/skills/marketing-frame-engine && git pull
```

`~/.claude/skills/`에 배치된 스킬은 Claude Code 및 Cowork 세션에서 자동으로 사용 가능합니다.

## Cowork Skills

25개 이상의 커스텀 스킬 중 하나입니다. 전체 카탈로그: [github.com/jasonnamii/cowork-skills](https://github.com/jasonnamii/cowork-skills)

## 라이선스

MIT License — 자유롭게 사용, 수정, 공유 가능합니다.
