# TransformerSNP500

transformer model을 사용한 snp500 예측

data는 2015-01-02 부터 2021-01-19까지의 데이터

아직은 장중 최고가만 이용하여 장중 최고가를 예측

![gif](./img/epoch.gif)

10 epoch별 변화 

blue: original data            red: test result

![future](./img/transformer-future100.png)

예측값

batch size를 키울 필요가 있음