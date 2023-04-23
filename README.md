# practice-np_pd_matplotlib
> `numpy, pandas, matplotlib` 튜토리얼 연습한 저장소입니다.

## 튜토리얼 URL
numpy, matplotlib
<br>
<https://scipy-lectures.org/intro/numpy/index.html>
<br><br>
pandas
<br>
<https://pandas.pydata.org/docs/user_guide/10min.html>
<br/>

<hr>

## 설정
* Python <= `3.10.10`
* `numpy`, `pandas`, `matplotlib(seaborn)`는 필수적으로 설치해주세요
* ipynb 를 위해서 `JupyterLab` 도 함께 설치해주세요.

<br>

```shell
$ python -m venv venv # 가상환경 구축
$ .\venv\Scripts\activate # 가상환경 구동
$ (venv) pip install  numpy pandas seaborn JupyterLab
$ (venv) jupyter-lab # 주피터 노트북 실행
```

### np.array 리스트 슬라이싱 할때 주의
    리스트를 슬라이싱 한다는 의미
    리스트의 부분을 가져와 보여주겠다는 뜻.
    즉. 같은 참조값을 가짐

    원본 데이터를 건드리지 않으려면 .copy 로 복사본 만들어 사용
    

## 지도학습
### 분류
    미리 정의된 여러 레이블 중 하나를 예측 하는 것
    
    N/Y로 구분 가능한 이진 분류 (스팸 메일)
    셋 이상의 클래스로 분류하는 다중 분류 (붓꽃 품종 예측)


### 회귀
    값을 예측하는 것

    연속적인 숫자를 예측 (주가 예측)
 
 
## KNeighbors
## K-최근접 이웃 모델의 복잡도와 일반화 사이의 관계
    이웃의 수가 너무 많을 수록 모델이 단순해지고(과소적합)
    => 너무 단순한 모델의 경우 훈련 정확도가 떨어짐
    이웃의 수가 너무 적을 경우 모델이 복잡해짐(과대적합)
    => 훈련 정확도는 높아지지만 일반화 정확도가 떨어짐


    K-최근접 이웃 알고리즘은  이해하기는 쉬우므로 더 복잡한 알고리즘을 적용하기 전에 시도해볼 수 있지만
    많은 특성을 가지는 데이터셋에서 잘 작동하지 예측이 느림



    
