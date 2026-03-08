# Track A-2: AutoEncoder·RUL 예지보전 심화

> **[v1.6.15]** 제조 AI 실무 교육과정 — Track A 심화 (8시간)

## 학습 목표

- AutoEncoder를 활용한 비지도 이상탐지 구현
- RUL(Remaining Useful Life) 예측 모델 개발
- NASA C-MAPSS 터빈 엔진 데이터 분석
- 예방정비 스케줄 설계 및 ROI 계산
- 실무 적용 파일럿 기획 초안 작성

## 실습 구성

| 순서 | 실습 | 소요 시간 | 데이터셋 |
|:----:|------|:---------:|---------|
| 1 | AutoEncoder 이상탐지 | 2.5h | KAMP id=26 (공정이상) |
| 2 | LSTM-AutoEncoder RUL 예측 | 3h | NASA C-MAPSS FD001 |
| 3 | 예방정비 스케줄 & ROI | 2.5h | 실습 데이터 |

**총 소요 시간**: 8시간

## 데이터셋

- **NASA C-MAPSS** (55MB): 터빈 엔진 수명 데이터 — [다운로드 안내](data/DATASET.md)
- **KAMP id=26**: 공정 이상 예지 데이터 (한국 스마트제조 포털)

## 연계 세션

- 선수: [Track A-1: 진동FFT 고장진단](https://github.com/manufacturing-ai-koreatechac/track-a1-vibration-fft)
- 후속: [X1: 에이전틱 제조AI](https://github.com/manufacturing-ai-koreatechac/x1-rag-agent)

## 시작하기

```bash
pip install torch scikit-learn pandas numpy matplotlib
jupyter lab
```

---
*KOREATECH 제조AI 실무 교육과정 v1.6.15 | 2026-03-04*
