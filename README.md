# 시장조사 스킬

주제 찾기부터 시장 스캔, 경쟁사 분석, 소셜 리스닝, STP, 팩트체크, 비즈니스 모델 캔버스, 전문가 검토까지 이어지는 **시장조사 스킬 8개**입니다. 특정 분야에 묶이지 않는 일반 스킬이고, 각 폴더의 `SKILL.md` 하나로 완결됩니다.

## 스킬

| 스킬 | 하는 일 | 결과 |
|---|---|---|
| [research-topic](research-topic/SKILL.md) | 관심 영역의 변화 신호를 훑어 리서치 질문 후보를 뽑고, 조사 가치를 비교해 주제 정의와 시장 정의 두 줄로 정함 | 메모리 2줄 |
| [market-scanner](market-scanner/SKILL.md) | 시장 정의, 동향(PEST), 규모(TAM·SAM·SOM 계산식), 시장 구조 | `market-landscape.md` + `.html` |
| [competitor-analysis](competitor-analysis/SKILL.md) | 직접·간접 경쟁사와 대체재, 포지셔닝·가격·채널, 3C·SWOT, 빈틈 | `competitive-intel.md` + `.html` |
| [customer-voice](customer-voice/SKILL.md) | 소셜 리스닝: 사용 장면, 불편, 대신 하는 것, 가설, 인터뷰 질문 | `customer-voice.md` + `.html` |
| [stp](stp/SKILL.md) | 조사 파일을 맞대어 교차 분석, 세분화·타겟팅·포지셔닝, 페르소나 | `stp.md` + `.html` |
| [fact-check](fact-check/SKILL.md) | 결과 파일의 숫자·제도·경쟁사 정보를 1차 출처로 확인해 ✅⚠️❌❓로 판정하고, 어느 파일을 어떤 순서로 고칠지 정리 | `fact-check.md` + `.html` |
| [business-canvas](business-canvas/SKILL.md) | 비즈니스 모델 캔버스 9칸, 맞물림·가정 점검, 무엇부터 할까 | `business-canvas.md` + `.html` |
| [expert-review](expert-review/SKILL.md) | 전문성이 다른 서브에이전트 3명에게 따로 검토받아 합의·이견·확신도로 종합. 전문가와 질문은 사용자가 고름 | `expert-review.md` + `.html` |

## 흐름

```
/research-topic → 주제 정의 + 시장 정의 (메모리)
        ↓
/market-scanner · /competitor-analysis · /customer-voice   (필요한 것만, 따로 진행 가능)
        ↓
/stp → /fact-check (새 채팅) → 조사 파일·STP 보완 (-v2)
        ↓
/business-canvas → /expert-review → /business-canvas 보완 (-v2)
```

- 각 조사 스킬은 작업 공간에 이미 있는 조사 파일을 먼저 읽고 이어서 씁니다.
- 검토 결과(팩트체크, 전문가 의견)를 주면 **보완 모드**로 바뀐 부분만 고친 `-v2` 파일을 만듭니다.
- 결과는 처음부터 두 파일로 나옵니다. `.md`는 원본이라 다음 단계에 주고, `.html`은 그림과 표로 정리한 보기용입니다.
- 조사 스킬은 "가볍게 / 보통 / 깊게"로 조사 깊이를 조절할 수 있습니다. 기본은 보통입니다.

## 분야 기준 넣기

스킬에는 특정 분야의 규칙이 들어 있지 않습니다. 분야별 기준(용어 정의, 데이터 소스, 해석 시 주의점, 체크리스트)은 **참고 자료 파일**로 작업 공간에 올리세요. 모든 스킬은 참고 자료가 있으면 먼저 읽고, 그 기준을 스킬 기준보다 우선합니다.

## 설치

### 팩트챗

프로젝트 채팅에서:

```
이 저장소의 스킬을 모두 가져와 줘: <이 저장소 링크>
```

스킬 저장 카드에서 저장한 뒤, 입력창에 `/`를 쳐서 8개가 보이는지 확인합니다.

### 그 밖의 에이전트

`SKILL.md` 형식(앞부분 `name`, `description`)을 읽는 에이전트라면 폴더째 스킬 디렉터리에 넣어 쓸 수 있습니다.
