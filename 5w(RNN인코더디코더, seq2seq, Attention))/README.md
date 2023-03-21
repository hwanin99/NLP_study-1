# 5w nlp

1. RNN Encoder, decoder / seq2seq / Attention 
- 1조 : 김윤경, 임지우, 김석현

[RNN Encoder,Decoder/seq2seq/Attention 세미나 바로가기](https://youtu.be/kFF3OHW8dMI)

---

2. Transformer 리뷰
- 2조 : 박지훈, 김성환, 은하영

[Transformer세미나 바로가기](https://youtu.be/OuKfYbsUQdw)

---- 

# 1. RNN Encoder, decoder / seq2seq / Attention 

** 자세한 설명은 pdf참조 **
> *** 세미나 pdf ***

![attention매커니즘이해사진](https://user-images.githubusercontent.com/108673913/226160699-cac7ab14-4dc3-49e4-aa45-8e96ae496a48.png)

> *** 공부 문서 정리 pdf ***

![seq2seq이해사진](https://user-images.githubusercontent.com/108673913/226160710-7d375b00-5378-405f-8847-e3f07b78b251.png)


- [seq2seq 참고한 블로그](https://bigdaheta.tistory.com/66)
- [Attention 참고한 블로그](https://blog.naver.com/sooftware/221784472231)
- 외적으로도 공부를 많이함

> - 코드 : _14_RNN_인코더_디코더.ipynb
----

# 2. Transformer
Transformer이란?

- 2017년 구글논문 *** <Attention is all you need> ***
- 기존 seq2seq구조인 인코더-디코더를 따르면서도, Attention만으로 구현한 모델
- 번역 성능에서 RNN보다 훨씬 뛰어남
    - seq2seq : RNN의 인코더 + context vector + RNN의 디코더
        - 교사강요 학습 (Teacher Forcing)
        - 단점 : 정보 손실 / 기울기 소실 -> Attention등장
    - Attention 매커니즘 :
        - 해당시점에서 예측할 단어와 연관이 있는 입력 단어부분을 좀 더 집중

*** 자세한 내용은 세미나 pdf 참조 ***
*** transformer 2조 공부 & 정리 (손글씨.pdf) *** 
> -   코드 - 챗봇 모델(짧은 학습을 위해 epoch, 활용 단어의 수를 줄임) : NLP_Transformer(챗봇).ipynb
> -  코드 - 챗봇 모델을 활용한 영한 번역기 모델(짧은 학습을 위해 epoch, 활용 단어의 수를 줄임) : eng-kor.ipynb


> - [참고-havard NLP](http://nlp.seas.harvard.edu/2018/04/03/attention.html)
> - [참고-havard NLP 해석 & 실험](https://cpm0722.github.io/pytorch-implementation/transformer)
> - [참고-wikidocs](https://wikidocs.net/31379)












