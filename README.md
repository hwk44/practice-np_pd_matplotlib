# practice-np_pd_matplotlib
> numpy, pandas, matplotlib 튜토리얼 연습한 저장소입니다.

## 참고 URL
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

## np.array 리스트 슬라이싱 할때 주의
    리스트를 슬라이싱 한다는 의미
    리스트의 부분을 가져와 보여주겠다는 뜻.
    즉. 같은 참조값을 가짐

    원본 데이터를 건드리지 않으려면 .copy 로 복사본 만들어 사용




    
