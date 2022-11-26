# 🐳 자연어 처리를 통한 환경 문제 인식 개선 🐳
### 양방향 LSTM 순환신경망을 통한 유튜브 제목 데이터 분석


<br/>

## 프로젝트 목표
:heavy_check_mark:  Selenium을 이용하여 유튜브 데이터 크롤링  <br/>
:heavy_check_mark:  WordVector을 이용하여 자연어 처리  <br/>
:heavy_check_mark:  양방향 LSTM 순환신경망을 이용하여 모델 학습  <br/>


* <h2>Web Crawling</h2>

  - 유튜브 제목 데이터 크롤링 <br/>
![image](https://user-images.githubusercontent.com/115959569/204072040-a642471b-d448-47e2-9aab-eaf620bdfb3c.png)<br/>


 - 유튜브 조회수 데이터 크롤링 <br/>
![image](https://user-images.githubusercontent.com/115959569/204072130-7bff18b8-ce6a-4bfe-9f0e-82f2f7d99b63.png)

* <h2>Data Preprocessing</h2>

  - 원본 데이터 <br/>
![image](https://user-images.githubusercontent.com/115959569/204072242-a6ed7f97-e332-4082-ba7e-923dec32b1d8.png)<br/>
    

  - 전처리 후 데이터 <br/>
![image](https://user-images.githubusercontent.com/115959569/204072228-8c5d73e2-7a50-4026-85de-ee6f03b6d176.png)<br/>

* <h2>Vectorization</h2>
    
  - 벡터화 한 데이터
![image](https://user-images.githubusercontent.com/115959569/204084817-157d9f57-e80d-4af4-8f91-3a2e6364907d.png)


* <h2>Machine Learning</h2>
    
  - 모델 학습
![image](https://user-images.githubusercontent.com/115959569/204085469-1ec8adea-7aee-47aa-8087-cb0347048688.png)


    

## :pushpin: 참고문헌
*  Selenium  
    - https://github.com/SOMJANG/Youtube_Comment_Crawler
*  Word Vector  
    - https://arxiv.org/pdf/1301.3781.pdf
    - https://github.com/KyungbokLee/korean_word2vec
*  Bidirectional LSTM 
    - http://www.bioinf.jku.at/publications/older/2604.pdf
    - https://cryptosalamander.tistory.com/175
    - https://www.tensorflow.org/api_docs/python/tf/keras/layers/Bidirectional
