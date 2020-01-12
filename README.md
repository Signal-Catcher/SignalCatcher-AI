# SignalCatcher-AI

## 간단 요약

### 1. Method.py

1. 대화 전체의 단어 빈도수를 feature로 뽑는 함수, 호감도를 구하는 함수
2. konlpy, sklearn library 필요
3. Main 함수로 실행, T = 1: label이 있는 대화의 feature를 저장, T = 2: 대화의 호감도 반환

cf) numpy 1.18.0에서는 동작하지 않음 1.17.0 버전 필요

pip uninstall numpy

pip install numpy==1.17.0
