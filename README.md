<img src="https://capsule-render.vercel.app/api?type=waving&color=auto&height=200&section=header&text=Exploration&fontSize=90" />

Aiffel에서 진행한 Exploration 노드관련 코드들입니다!

<div align="center"> ⚒️ Tools ⚒️ </div>
<div align="center">
	<img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=Python&logoColor=white" />
	<img src="https://img.shields.io/badge/Tensorflow-FF6F00?style=flat&logo=Tensorflow&logoColor=white" />
	<img src="https://img.shields.io/badge/scikit-learn-F7931E?style=flat&logo=scikit-learn&logoColor=white" />
</div>


-  ### [1. 멋진 단어사전 만들기](https://github.com/minsung6333/AIFFEL_Project/blob/main/1_%E1%84%86%E1%85%A5%E1%86%BA%E1%84%8C%E1%85%B5%E1%86%AB_%E1%84%83%E1%85%A1%E1%86%AB%E1%84%8B%E1%85%A5%E1%84%89%E1%85%A1%E1%84%8C%E1%85%A5%E1%86%AB_%E1%84%86%E1%85%A1%E1%86%AB%E1%84%83%E1%85%B3%E1%86%AF%E1%84%80%E1%85%B5_%5B%E1%84%91%E1%85%B3%E1%84%85%E1%85%A9%E1%84%8C%E1%85%A6%E1%86%A8%E1%84%90%E1%85%B3%5D.ipynb)
	- SentencePiece를 통해 만든 Tokenizer 만들기
	- Konlpy 형태소 분석기와 비교 분석 진행
- ### [2. 뉴스 카테고리 다중분류](https://github.com/minsung6333/AIFFEL_Project/blob/main/2_%EB%89%B4%EC%8A%A4_%EC%B9%B4%ED%85%8C%EA%B3%A0%EB%A6%AC_%EB%8B%A4%EC%A4%91%EB%B6%84%EB%A5%98_%5B%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8%5D.ipynb)
	- 뉴스 카테고리 다중분류 진행
 	- naive_bayes, Complement_Naive_Bayes, LogisticRegression, Linear_Support_Vector_Classifier, DecisionTree, RandomForest, GradientBoosting, Voting 비교분석

- ### [3. 모든 장르 간 편향성 측정해보기](https://github.com/minsung6333/AIFFEL_Project/blob/main/3_%EB%AA%A8%EB%93%A0_%EC%9E%A5%EB%A5%B4_%EA%B0%84_%ED%8E%B8%ED%96%A5%EC%84%B1_%EC%B8%A1%EC%A0%95%ED%95%B4_%EB%B3%B4%EA%B8%B0_%5Bproject%5D.ipynb)
	- 형태소 분석기를 이용하여 품사가 명사인 경우 해당 단어를 추출하기
	- 추출된 결과로 embedding model 만들기
  
- ### [4. Seq2Seq로 번역기 만들기](https://github.com/minsung6333/AIFFEL_Project/blob/main/4_Seq2Seq%EB%A1%9C_%EB%B2%88%EC%97%AD%EA%B8%B0_%EB%A7%8C%EB%93%A4%EA%B8%B0_%5B%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8%5D.ipynb)
	- AI-HUB에 있는 '일상생활 및 구어체 한-영 번역 병렬 말뭉치 데이터'를 사용하여 번역기
  
- ### [5. Transformer 번역기 만들기](https://github.com/minsung6333/AIFFEL_Project/blob/main/5_%E1%84%90%E1%85%B3%E1%84%85%E1%85%A6%E1%86%AB%E1%84%89%E1%85%B3%E1%84%91%E1%85%A9%E1%84%86%E1%85%A5_%E1%84%87%E1%85%A5%E1%86%AB%E1%84%8B%E1%85%A7%E1%86%A8%E1%84%80%E1%85%B5_%E1%84%86%E1%85%A1%E1%86%AB%E1%84%83%E1%85%B3%E1%86%AF%E1%84%80%E1%85%B5_%5B%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8%5D.ipynb)
	- Transformer 번역기 만들기
  
- ### [6. 번역가는 대화에도 능하다](https://github.com/minsung6333/AIFFEL_Project/blob/main/6_%E1%84%87%E1%85%A5%E1%86%AB%E1%84%8B%E1%85%A7%E1%86%A8%E1%84%80%E1%85%A1%E1%84%82%E1%85%B3%E1%86%AB_%E1%84%83%E1%85%A2%E1%84%92%E1%85%AA%E1%84%8B%E1%85%A6%E1%84%83%E1%85%A9_%E1%84%82%E1%85%B3%E1%86%BC%E1%84%92%E1%85%A1%E1%84%83%E1%85%A1_%5B%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8%5D.ipynb)
	- 데이터 증강 후 대화 챗봇 만들기 프로젝트
  
- ### [7. Mini BERT 만들기](https://github.com/minsung6333/AIFFEL_Project/blob/main/7_BERT_pretrained_model_%EC%A0%9C%EC%9E%91_%5B%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8%5D.ipynb)
	- 전체 파라미터 사이즈가 1M 정도가 되는 아주 작은 mini BERT 모델을 만들기


- ### [8. HuggingFace 커스텀 프로젝트 만들기](https://github.com/minsung6333/AIFFEL_Project/blob/main/8_HuggingFace_%E1%84%8F%E1%85%A5%E1%84%89%E1%85%B3%E1%84%90%E1%85%A5%E1%86%B7_%E1%84%91%E1%85%B3%E1%84%85%E1%85%A9%E1%84%8C%E1%85%A6%E1%86%A8%E1%84%90%E1%85%B3_%E1%84%86%E1%85%A1%E1%86%AB%E1%84%83%E1%85%B3%E1%86%AF%E1%84%80%E1%85%B5_%5B%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8%5D.ipynb)
	-  model(klue/ber-base)를 활용하여 NSMC(Naver Sentiment Movie Corpus) task를 도전
- ### [9. LLM 최신 모델 구현](https://github.com/minsung6333/AIFFEL_Project/blob/main/9_LLM_%EC%B5%9C%EC%8B%A0_%EB%AA%A8%EB%8D%B8_%EA%B5%AC%ED%98%84_%5B%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8%5D.ipynb)
	- KoChatGPT 소스코드를 바탕으로 다양한 모델 개선 전략을 선택해 여러분만의 custom ChatGPT를 개발
