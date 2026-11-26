# 국방 인공지능 — 실습 코드

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/2038prob/defense-ai-textbook-code/blob/main/notebooks/%EC%8B%A4%EC%8A%B5_02_PyTorch_%EA%B8%B0%EC%B4%88.ipynb)
![license](https://img.shields.io/badge/license-MIT-green)
![python](https://img.shields.io/badge/python-3.9%2B-blue)
![pytorch](https://img.shields.io/badge/PyTorch-2.x-ee4c2c)

교재 **「데이터·모델·학습이론으로 배우는 국방 인공지능」**(권현·이준·맹주본)의 실습 코드 저장소입니다.
본문의 파이썬 예제·실습을 **장별 Jupyter 노트북**으로 정리했으며, 각 노트북은 클릭 한 번으로 Google
Colab에서 바로 실행할 수 있습니다.

## 빠른 시작 (Colab, 설치 불필요)
1. 아래 표에서 원하는 장의 **Colab 배지**를 클릭합니다.
2. 노트북이 열리면 **맨 위 `setup` 셀부터 위에서 아래로** 순서대로 실행합니다.
   (앞 셀에서 정의한 변수를 뒤 셀이 이어 쓰므로 순서가 중요합니다.)
3. GPU가 필요하면 Colab 메뉴의 *런타임 → 런타임 유형 변경 → GPU* 를 선택하세요.

## 로컬 실행
```bash
git clone https://github.com/2038prob/defense-ai-textbook-code.git
cd defense-ai-textbook-code
pip install -r requirements.txt
jupyter lab      # 또는 jupyter notebook, VS Code
```

## 장별 노트북
교재는 2026-11 개정에서 4부 12장(기초수학과 PyTorch → 컴퓨터 비전 → 자연어 처리 → 영상과 언어의 융합과 실전)으로 재편되었습니다. 1장(기초수학)과 10장(멀티모달)은 노트북을 준비 중입니다.

| 장 | 실습 노트북 | Colab |
|---:|---|---|
| 2 | [PyTorch 기초](notebooks/%EC%8B%A4%EC%8A%B5_02_PyTorch_%EA%B8%B0%EC%B4%88.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/2038prob/defense-ai-textbook-code/blob/main/notebooks/%EC%8B%A4%EC%8A%B5_02_PyTorch_%EA%B8%B0%EC%B4%88.ipynb) |
| 3 | [데이터 파이프라인과 MLP](notebooks/%EC%8B%A4%EC%8A%B5_03_%EB%8D%B0%EC%9D%B4%ED%84%B0_%ED%8C%8C%EC%9D%B4%ED%94%84%EB%9D%BC%EC%9D%B8%EA%B3%BC_MLP.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/2038prob/defense-ai-textbook-code/blob/main/notebooks/%EC%8B%A4%EC%8A%B5_03_%EB%8D%B0%EC%9D%B4%ED%84%B0_%ED%8C%8C%EC%9D%B4%ED%94%84%EB%9D%BC%EC%9D%B8%EA%B3%BC_MLP.ipynb) |
| 4 | [CNN 기초](notebooks/%EC%8B%A4%EC%8A%B5_04_CNN_%EA%B8%B0%EC%B4%88.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/2038prob/defense-ai-textbook-code/blob/main/notebooks/%EC%8B%A4%EC%8A%B5_04_CNN_%EA%B8%B0%EC%B4%88.ipynb) |
| 5 | [전이학습](notebooks/%EC%8B%A4%EC%8A%B5_05_%EC%A0%84%EC%9D%B4%ED%95%99%EC%8A%B5.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/2038prob/defense-ai-textbook-code/blob/main/notebooks/%EC%8B%A4%EC%8A%B5_05_%EC%A0%84%EC%9D%B4%ED%95%99%EC%8A%B5.ipynb) |
| 6 | [비전 트랜스포머, 객체 탐지와 추적](notebooks/%EC%8B%A4%EC%8A%B5_06_%EB%B9%84%EC%A0%84_%ED%8A%B8%EB%9E%9C%EC%8A%A4%ED%8F%AC%EB%A8%B8_%EA%B0%9D%EC%B2%B4_%ED%83%90%EC%A7%80%EC%99%80_%EC%B6%94%EC%A0%81.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/2038prob/defense-ai-textbook-code/blob/main/notebooks/%EC%8B%A4%EC%8A%B5_06_%EB%B9%84%EC%A0%84_%ED%8A%B8%EB%9E%9C%EC%8A%A4%ED%8F%AC%EB%A8%B8_%EA%B0%9D%EC%B2%B4_%ED%83%90%EC%A7%80%EC%99%80_%EC%B6%94%EC%A0%81.ipynb) |
| 7 | [NLP와 트랜스포머 기초](notebooks/%EC%8B%A4%EC%8A%B5_07_NLP%EC%99%80_%ED%8A%B8%EB%9E%9C%EC%8A%A4%ED%8F%AC%EB%A8%B8_%EA%B8%B0%EC%B4%88.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/2038prob/defense-ai-textbook-code/blob/main/notebooks/%EC%8B%A4%EC%8A%B5_07_NLP%EC%99%80_%ED%8A%B8%EB%9E%9C%EC%8A%A4%ED%8F%AC%EB%A8%B8_%EA%B8%B0%EC%B4%88.ipynb) |
| 8 | [대형 언어 모델(LLM) 활용](notebooks/%EC%8B%A4%EC%8A%B5_08_%EB%8C%80%ED%98%95_%EC%96%B8%EC%96%B4_%EB%AA%A8%EB%8D%B8_LLM_%ED%99%9C%EC%9A%A9.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/2038prob/defense-ai-textbook-code/blob/main/notebooks/%EC%8B%A4%EC%8A%B5_08_%EB%8C%80%ED%98%95_%EC%96%B8%EC%96%B4_%EB%AA%A8%EB%8D%B8_LLM_%ED%99%9C%EC%9A%A9.ipynb) |
| 9 | [생성 모델](notebooks/%EC%8B%A4%EC%8A%B5_09_%EC%83%9D%EC%84%B1_%EB%AA%A8%EB%8D%B8.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/2038prob/defense-ai-textbook-code/blob/main/notebooks/%EC%8B%A4%EC%8A%B5_09_%EC%83%9D%EC%84%B1_%EB%AA%A8%EB%8D%B8.ipynb) |
| 11 | [모델 최적화와 실전 배포](notebooks/%EC%8B%A4%EC%8A%B5_11_%EB%AA%A8%EB%8D%B8_%EC%B5%9C%EC%A0%81%ED%99%94%EC%99%80_%EC%8B%A4%EC%A0%84_%EB%B0%B0%ED%8F%AC.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/2038prob/defense-ai-textbook-code/blob/main/notebooks/%EC%8B%A4%EC%8A%B5_11_%EB%AA%A8%EB%8D%B8_%EC%B5%9C%EC%A0%81%ED%99%94%EC%99%80_%EC%8B%A4%EC%A0%84_%EB%B0%B0%ED%8F%AC.ipynb) |
| 12 | [종합 프로젝트 가이드](notebooks/%EC%8B%A4%EC%8A%B5_12_%EC%A2%85%ED%95%A9_%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8_%EA%B0%80%EC%9D%B4%EB%93%9C.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/2038prob/defense-ai-textbook-code/blob/main/notebooks/%EC%8B%A4%EC%8A%B5_12_%EC%A2%85%ED%95%A9_%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8_%EA%B0%80%EC%9D%B4%EB%93%9C.ipynb) |
| 부록 A | [참조 자료 종합 가이드](notebooks/%EC%8B%A4%EC%8A%B5_A_%EC%B0%B8%EC%A1%B0_%EC%9E%90%EB%A3%8C_%EC%A2%85%ED%95%A9_%EA%B0%80%EC%9D%B4%EB%93%9C.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/2038prob/defense-ai-textbook-code/blob/main/notebooks/%EC%8B%A4%EC%8A%B5_A_%EC%B0%B8%EC%A1%B0_%EC%9E%90%EB%A3%8C_%EC%A2%85%ED%95%A9_%EA%B0%80%EC%9D%B4%EB%93%9C.ipynb) |

### 온라인 보충 노트북
인쇄본에서 빠지고 온라인 보충으로 옮긴 장의 노트북입니다(`notebooks/online/`).

| 보충 | 실습 노트북 | Colab |
|---:|---|---|
| S1-1 | [강화학습 기초](notebooks/online/%EC%98%A8%EB%9D%BC%EC%9D%B8%EB%B3%B4%EC%B6%A9_S1-1_%EA%B0%95%ED%99%94%ED%95%99%EC%8A%B5_%EA%B8%B0%EC%B4%88.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/2038prob/defense-ai-textbook-code/blob/main/notebooks/online/%EC%98%A8%EB%9D%BC%EC%9D%B8%EB%B3%B4%EC%B6%A9_S1-1_%EA%B0%95%ED%99%94%ED%95%99%EC%8A%B5_%EA%B8%B0%EC%B4%88.ipynb) |
| S1-2 | [DQN과 현대 심층 강화학습](notebooks/online/%EC%98%A8%EB%9D%BC%EC%9D%B8%EB%B3%B4%EC%B6%A9_S1-2_DQN%EA%B3%BC_%ED%98%84%EB%8C%80_%EC%8B%AC%EC%B8%B5_%EA%B0%95%ED%99%94%ED%95%99%EC%8A%B5.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/2038prob/defense-ai-textbook-code/blob/main/notebooks/online/%EC%98%A8%EB%9D%BC%EC%9D%B8%EB%B3%B4%EC%B6%A9_S1-2_DQN%EA%B3%BC_%ED%98%84%EB%8C%80_%EC%8B%AC%EC%B8%B5_%EA%B0%95%ED%99%94%ED%95%99%EC%8A%B5.ipynb) |
| S1-3 | [다중 에이전트 강화학습](notebooks/online/%EC%98%A8%EB%9D%BC%EC%9D%B8%EB%B3%B4%EC%B6%A9_S1-3_%EB%8B%A4%EC%A4%91_%EC%97%90%EC%9D%B4%EC%A0%84%ED%8A%B8_%EA%B0%95%ED%99%94%ED%95%99%EC%8A%B5.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/2038prob/defense-ai-textbook-code/blob/main/notebooks/online/%EC%98%A8%EB%9D%BC%EC%9D%B8%EB%B3%B4%EC%B6%A9_S1-3_%EB%8B%A4%EC%A4%91_%EC%97%90%EC%9D%B4%EC%A0%84%ED%8A%B8_%EA%B0%95%ED%99%94%ED%95%99%EC%8A%B5.ipynb) |
| S1-4 | [AlphaGo, MCTS와 지휘결심 지원 시스템](notebooks/online/%EC%98%A8%EB%9D%BC%EC%9D%B8%EB%B3%B4%EC%B6%A9_S1-4_AlphaGo_MCTS%EC%99%80_%EC%A7%80%ED%9C%98%EA%B2%B0%EC%8B%AC_%EC%A7%80%EC%9B%90_%EC%8B%9C%EC%8A%A4%ED%85%9C.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/2038prob/defense-ai-textbook-code/blob/main/notebooks/online/%EC%98%A8%EB%9D%BC%EC%9D%B8%EB%B3%B4%EC%B6%A9_S1-4_AlphaGo_MCTS%EC%99%80_%EC%A7%80%ED%9C%98%EA%B2%B0%EC%8B%AC_%EC%A7%80%EC%9B%90_%EC%8B%9C%EC%8A%A4%ED%85%9C.ipynb) |
| S2 | [시계열과 LSTM](notebooks/online/%EC%98%A8%EB%9D%BC%EC%9D%B8%EB%B3%B4%EC%B6%A9_S2_%EC%8B%9C%EA%B3%84%EC%97%B4%EA%B3%BC_LSTM.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/2038prob/defense-ai-textbook-code/blob/main/notebooks/online/%EC%98%A8%EB%9D%BC%EC%9D%B8%EB%B3%B4%EC%B6%A9_S2_%EC%8B%9C%EA%B3%84%EC%97%B4%EA%B3%BC_LSTM.ipynb) |
| S3 | [이상 탐지](notebooks/online/%EC%98%A8%EB%9D%BC%EC%9D%B8%EB%B3%B4%EC%B6%A9_S3_%EC%9D%B4%EC%83%81_%ED%83%90%EC%A7%80.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/2038prob/defense-ai-textbook-code/blob/main/notebooks/online/%EC%98%A8%EB%9D%BC%EC%9D%B8%EB%B3%B4%EC%B6%A9_S3_%EC%9D%B4%EC%83%81_%ED%83%90%EC%A7%80.ipynb) |
| S4 | [자세 추정과 동작 인식](notebooks/online/%EC%98%A8%EB%9D%BC%EC%9D%B8%EB%B3%B4%EC%B6%A9_S4_%EC%9E%90%EC%84%B8_%EC%B6%94%EC%A0%95%EA%B3%BC_%EB%8F%99%EC%9E%91_%EC%9D%B8%EC%8B%9D.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/2038prob/defense-ai-textbook-code/blob/main/notebooks/online/%EC%98%A8%EB%9D%BC%EC%9D%B8%EB%B3%B4%EC%B6%A9_S4_%EC%9E%90%EC%84%B8_%EC%B6%94%EC%A0%95%EA%B3%BC_%EB%8F%99%EC%9E%91_%EC%9D%B8%EC%8B%9D.ipynb) |
| S5 | [AI 윤리와 공정성](notebooks/online/%EC%98%A8%EB%9D%BC%EC%9D%B8%EB%B3%B4%EC%B6%A9_S5_AI_%EC%9C%A4%EB%A6%AC%EC%99%80_%EA%B3%B5%EC%A0%95%EC%84%B1.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/2038prob/defense-ai-textbook-code/blob/main/notebooks/online/%EC%98%A8%EB%9D%BC%EC%9D%B8%EB%B3%B4%EC%B6%A9_S5_AI_%EC%9C%A4%EB%A6%AC%EC%99%80_%EA%B3%B5%EC%A0%95%EC%84%B1.ipynb) |

> 재편 전(17장판) 번호의 노트북은 브랜치 [`legacy/v1-17ch`](https://github.com/2038prob/defense-ai-textbook-code/tree/legacy/v1-17ch)에 그대로 남아 있습니다.

## 안내
- `⚠️ 설명용 조각` 표시가 붙은 셀은 개념을 보여 주는 코드로, 그대로는 실행되지 않을 수 있습니다.
- `실행 결과 예시`는 교재에 실린 예시 출력이며, 난수·환경에 따라 실제 값은 다를 수 있습니다.
- 코드는 교재의 설명 흐름을 따르므로 학습용에 최적화되어 있습니다(운용 배포용 최적화 코드가 아닙니다).
- 오류·개선 제안은 이 저장소의 **Issues** 로 알려 주세요.

## 라이선스
코드는 [MIT License](LICENSE)로 배포합니다. 교재 본문·그림의 저작권은 별도이며 저자에게 있습니다.

---
교재: 「국방 인공지능」  ·  저장소: https://github.com/2038prob/defense-ai-textbook-code
