모델의 output과 target은 (N, input winodw) 형태의 tensor이다. 

우선은 위의 tensor를 N비트의 수로 바꾸어준다. 1차원의 시뭔스중 맨 뒤의 두개를 비교하여 특정 퍼센트 이상 상승 했을 경우 비트를 1 로 dkslaus 0으로 채워준다. 그리고 target과 output의 bit를 비교해주는 것은


$$
f(output - target) = {1 \over n}{\sum_{i=1}^N |output_i-target_i| }
$$


이다.



