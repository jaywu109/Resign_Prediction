# Resign_Prediction
### AIdea 員工離職預測：統計諮詢小組報告    
   
員工離職的因素百百種，身為企業決策者，總是希望能廣納賢士壯大公司。若能夠清楚地掌握員工離職的原因，不但能加以改善留住人才，還能避免公司虧損甚至倒閉。而對於準畢業生的我們而言，也想在進入職場前，了解什麼樣的因素會使人想要烙跑，除了能幫助我們找到適合自己的職場元素，也可用做前車之鑑提醒自己，不要落入社會陷阱。  
  
本報告使用了AIdea人工智慧共創平台上的一筆關於員工離職的資料，我們欲使用員工與工作單位的特徵去預測這位員工這一年會不會離職，經過缺失值的處理再做One hot encoding處理類別變數之後，將資料切成2014~2016年為train、2017為test。使用以下幾種方法：logistic Regression, Decision Tree, AdaBoost, KNN, Random Forest, KNN, Naive Bayes, QDA, Neural Network，然後以SMOTE套件解決離職樣本過少資料不平衡的問題，使用train資料訓練出能預測員工這一年是否會離職的模型，最後使用test資料以F beta-score指標評估每一個模型的表現。

## 分析流程
![image](https://user-images.githubusercontent.com/36630295/125032772-08730e00-e0c1-11eb-97da-d26db4762427.png)

## 變數重要性分析
![image](https://user-images.githubusercontent.com/36630295/125032870-280a3680-e0c1-11eb-99ef-18034bb98af3.png)

## Ensemble Method
![image](https://user-images.githubusercontent.com/36630295/125032947-440dd800-e0c1-11eb-8fc8-f6b58181e5a2.png)  
![image](https://user-images.githubusercontent.com/36630295/125032970-4d974000-e0c1-11eb-999f-a2895382b3ad.png)
