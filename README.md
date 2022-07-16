# hustar_BigdataAnalysis
Hustar에서 진행된 BigdataAnalysis 관련 Source code file 입니다.  <br><br>


### GameDataAnalysis
- LoL Game data를 분석
- numpy, pandas 기본 사용법, 데이터 탐색 위주

### Student_BostonHouse
- matplotlib.pyplot, seaborn을 사용한 scatter, distplot 구현
- Linear regression 사용
- example1) Student의 키로, 몸무게 예측
- example2) Boston 집 값 예측

### AromaWine
- seaborn을 사용한 heatmap 구현
- Ridge regression 사용, mse & r2_score, adjusted r2 score 계산

### Smarket
- seaborn의 pairplot을 사용한 Data EDA / matplotlib.pyplot의 scatter를 활용한 범주별 데이터 분포 확인
- LDA, QDA 구현

### MNIST_LogisticRegression
- MNIST dataset 탐색
- Logistic regression, confusion matrix 구현

### Contest_SVM
- Data preprocessing (NULL값 제거)
- support vector machine 구현 (linear, polynomial, rbf, sigmoid)
- Accuracy, F1 score, confusion matrix, precision score, recall score 계산 (C, gamma 조정하며 다양한 시도)

### Hepatitis_tree_graphviz
- Hepatitis Data를 DecisionTreeClassifier로 학습 및 추론
- graphviz를 사용한 시각화
- post-pruning을 적용

### Wine_boosting
- Wine data 분석, StandardScaler로 표준화 진행
- RandomForest, DecisionTree, AdaBoost, XGBoost, LogisticRegression 모델의 성능 비교
- StratifiedKFold와 cross validation으로 검증
- GridSearchCV와 RandomizedSearchCV로 최적의 파라미터 탐색

### iris_Clustering
- iris data 분석
- KMeans Clustering, Gaussian Mixture 구현
- seaborn, Axes3D, plotly를 사용한 2, 3차 시각화

### PCA_regression
- Boston 집 값 Data 활용
- PCA를 사용한 차원 축소법 연구 (작은 MSE, 높은 Accuracy를 가지는 주성분 개수 추출)
- K-fold validation, GridSearchCV로 최적의 하이퍼파라미터 추출, Linear Regression과 SVM으로 검증

