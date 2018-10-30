# Sales-volume-forecasting-and-analysis-system
#### 銷售量預測暨分析系統─以蘇州旅宿業為例
#### 發現蘇州的酒店有銷售量震盪的趨勢，因此和夥伴們一起開發了銷售量預測系統
＃ 系統介面：http://ec2-54-180-26-182.ap-northeast-2.compute.amazonaws.com/
#登入畫面

![image](https://github.com/mv123453715/Sales-volume-forecasting-and-analysis-system/blob/master/%E7%99%BB%E5%85%A5%E7%95%AB%E9%9D%A2.PNG)
 
+ [功能一：銷售現況分析]
可以看出2015年1月~2016年1月資料的概況
![image](https://github.com/mv123453715/Sales-volume-forecasting-and-analysis-system/blob/master/%E9%8A%B7%E5%94%AE%E7%8F%BE%E6%B3%81%E5%88%86%E6%9E%90.PNG)
 


+ [功能二：銷售量預測]
將2015年1月~2016年1月資料投入做訓練
運用演算法多元回歸與XGBOOST然後做模型融合後降低誤差
建模後預測2016年2月的銷售量
![image](https://github.com/mv123453715/Sales-volume-forecasting-and-analysis-system/blob/master/%E9%8A%B7%E5%94%AE%E9%87%8F%E9%A0%90%E6%B8%AC.PNG)
 
原理
![image](https://github.com/mv123453715/Sales-volume-forecasting-and-analysis-system/blob/master/%E9%8A%B7%E5%94%AE%E9%87%8F%E9%A0%90%E6%B8%AC%E5%8E%9F%E7%90%86.PNG)
 
+ [功能三：價格敏感計]
利用LTSM預測出銷售量與價格之間的關係

![image](https://github.com/mv123453715/Sales-volume-forecasting-and-analysis-system/blob/master/%E5%83%B9%E6%A0%BC%E6%95%8F%E6%84%9F%E8%A8%88.PNG)

+[原理]
![image](https://github.com/mv123453715/Sales-volume-forecasting-and-analysis-system/blob/master/%E5%83%B9%E6%A0%BC%E6%95%8F%E6%84%9F%E8%A8%88%E5%8E%9F%E7%90%86.PNG)

+ [功能四：評論風向球]
蒐集網路上客戶的評論進行好壞的分類，找出影響銷售量的因子
![image](https://github.com/mv123453715/Sales-volume-forecasting-and-analysis-system/blob/master/%E8%A9%95%E8%AB%96%E9%A2%A8%E5%90%91%E7%90%83.PNG)

+[原理]
![image](https://github.com/mv123453715/Sales-volume-forecasting-and-analysis-system/blob/master/%E8%A9%95%E8%AB%96%E9%A2%A8%E5%90%91%E7%90%83%20%E5%8E%9F%E7%90%86.PNG)

+ [功能五：銷售策略分析]
運用決策樹與分類找出銷售量好的規則

![image](https://github.com/mv123453715/Sales-volume-forecasting-and-analysis-system/blob/master/%E9%8A%B7%E5%94%AE%E7%AD%96%E7%95%A5.PNG)


+[原理]
![image](https://github.com/mv123453715/Sales-volume-forecasting-and-analysis-system/blob/master/%E9%8A%B7%E5%94%AE%E7%AD%96%E7%95%A5%E5%8E%9F%E7%90%86.PNG)

+[感謝名單]
+[Josh, Filex, Angie, Gary, James, Kia, Iris,Tim]

