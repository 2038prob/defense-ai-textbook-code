# 「국방 인공지능」 실습 코드 노트북

본문(교재)에 실린 파이썬 실습·예제 코드를 **장별 Jupyter 노트북(.ipynb)** 으로 정리한 배포용 묶음입니다.
각 노트북은 해당 장의 코드를 본문 순서대로 담고 있으며, 실습·예제 제목과 짧은 설명을 마크다운 셀로 붙였습니다.

## 구성
- `실습_01_PyTorch_기초.ipynb` ~ `실습_18_참조_자료_종합_가이드.ipynb` (총 18개, 장별 1개)
- 각 노트북 = 제목/안내 마크다운 → (섹션 헤더 → 설명 → 코드셀) 반복. 일부 셀은 개념 설명용 조각 코드입니다.

## 실행 환경
```bash
pip install torch torchvision numpy matplotlib scipy
# (선택) 오디오·트랜스포머 실습: pip install torchaudio transformers
jupyter lab   # 또는 jupyter notebook, VS Code, Colab 업로드
```
- GPU가 없어도 대부분 CPU에서 동작합니다(학습이 느릴 수 있음). Colab 사용 시 런타임 유형을 GPU로 두면 좋습니다.
- 노트북 안의 코드는 교재의 설명 흐름에 맞춘 것이라, 일부 조각 셀은 앞 셀에서 정의한 변수·모델을 이어 씁니다. **위에서부터 순서대로** 실행하세요.
- ``실행 결과 예시`` 마크다운 셀은 교재에 실린 예시 출력이며, 난수·환경에 따라 실제 값은 다를 수 있습니다.

## 재생성
교재 원본(`source/naeji_main.tex`)이 갱신되면 아래로 노트북을 다시 만들 수 있습니다.
```bash
cd source
python make_notebooks.py     # -> ../notebooks/*.ipynb 재생성
```

> 주의: 코드셀은 교재의 `lstlisting` 블록에서 자동 추출되며, 한글 주석의 조판용 이스케이프(`\%` `\_` `~` `^`)는
> 실행 가능한 형태로 복원됩니다.
