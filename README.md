# :jack_o_lantern: TFIDF-WordCloud
> 본 코드는 각 영화의 수집된 부정/긍정 리뷰 데이터셋의 특징을 분석하기 위해 TF-IDF의 가중치와 WordCloud를 같이 적용하여 시각화를 수행합니다.

## :apple: 기대 효과
**1. Consumers:**
> Before selecting a movie, they can reduce the effort of going through positive or negative reviews by checking the key sentences from movie reviews.
 
**2. Movie Producers:**
> They can check the key evaluations of the movies they have produced, accept positive feedback, and make improvements based on negative feedback.

**3. Movie Platforms:**
> They can recommend suitable movies to users not only based on the genre preferences of the movies but also on the evaluation preferences of users.

## 🌲Working Enviornment
* torch
* seaborn
* numpy
* pandas
* nltk
* scikit-learn
* wordcloud
* googletrans

## 🗃️[Dataset](https://github.com/ZangZaeSeok/TFIDF-WordCloud/tree/main/dataset)
* 3 종류의 영화 리뷰 데이터셋을 활용합니다: 1) 앤트맨3, 2) 존윅4, 3) 가디언즈 오브 갤럭시3
* 리뷰 데이터셋은 imdb에서 수집되었으며, 영화의 부정적 또는 긍정적인 특성을 파악하기 위해, 부정적인 리뷰와 긍정적인 리뷰에 대해 미리 수집하였습니다.

## 🗂️각 디렉토리별 설명
**dataset:**
> 각 영화 리뷰 데이터들이 pickle 형식으로 저장되어 있습니다. 해당 pickle 파일을 로드하면 pandas dataframe 형식의 파일을 확인할 수 있습니다.

**default-wordcloud**
> 본 연구에서 제안하기 이전 단계의 단순하게 빈도수를 활용하여 wordcloud 시각화를 수행한 코드들이 있습니다.

**tfidf-wordcloud**
> 본 연구에서 제안하는 빈도수를 tf-idf 가중치로 대체하여 wordcloud 시각화를 수행하는 코드입니다. 이 경우, 긍정 또는 부정적인 다른 특성을 가진 리뷰에서 발견되지 않는 중요한 특성들을 확인할 수 있게 됩니다.

## 🔎 데이터 시각화
- 앤트맨 3의 리뷰에 대한 분석 시각화 결과입니다.
### [default-wordcloud](https://github.com/ZangZaeSeok/TFIDF-WordCloud/blob/main/default-wordcloud/%E1%84%8B%E1%85%A2%E1%86%AB%E1%84%90%E1%85%B3%E1%84%86%E1%85%A2%E1%86%AB-No%20processing.ipynb)


