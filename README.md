# machine-learning
machinelearning projects
# 기계학습 및 실습 과제

작성자: 인공지능융합학부 안효승(2019100021)

기계학습 kaggle 타이타닉 데이터셋 분석과제를 수행하였다.


터미널을 사용해 개발환경을 구축해두었다.
기본적으로 mkdir을 이용해 Projects, assignment 폴더를 생성하였고
cd .\Projects\assignment 디렉토리 이동을 하였고 
.\.venv\Scripts\Activate.ps1 로 가상환경을 사용하였다. 
pip install pandas matplotlib scikit-learn을 설치하여 구현 및 분석 준비를 하였다.


분석 목적으로는 객실, 성별, 나이대 별로 생존율이다.

우선 1등급, 2등급, 3등급의 객실이 존재하였고 등급별 생존율을 분석하였다. 분석결과 등급이 높을 수록 생존율이 높았고 1등급:62% 2등급:47% 3등급:24%의 생존율을 보였다.

또한 남성 여성의 성별 별 생존율도 분석하였다. 분석 결과로는 남성 생존율 18퍼센트, 여성 생존율 74퍼센트가 나왔다.
여성의 생존율이 높았는데 그렇다면 로얄객실 여성의 생존율은 얼마나 될까 하는 궁금중에 구현해본 결과 무려 96%라는 높은 생존율을 확인할 수 있었다.
로얄 객실 18세이하 아이들의 생존율 또한 87%라는 높은 생존율을 보여주고 있다.

연령별 분석은 유아층(0-9세), 청년층(20-39세), 중년층(40-59세), 노년층(60-69세)로 구현하였고
유아층:59% 청년층:35% 중년층:39% 노년층:31%인 것을 확인할 수 있었다.
