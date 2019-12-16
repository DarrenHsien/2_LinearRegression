主題 : 房價預測

X = 建物移轉總面積平方公尺 , or plus 屋齡 

y = 總價元

CostFunction : MSE/2

Evaluate Function : R-Square OR MSE

方法 :

  使用線性迴歸:
  
  (單特徵)
  
    -Scikit-Learn SGDRegressor(梯度下降)
    
    -Scikit-Learn LinearRegression(正規方程_公式解)
  
  
  (多特徵)
  
  多變項(加入兩組或兩組以上的特徵來進行預測)
  
    -Scikit-Learn SGDRegressor(梯度下降)
    
    -Scikit-Learn LinearRegression(正規方程)
  
  
  使用非線性迴歸:
  
  (單特徵)
  
  多項式(Polynomial) 非線性迴歸(from sklearn.preprocessing import PolynomialFeatures)
  
    -Scikit-Learn LinearRegression(正規方程_公式解)
  
    

評估標準 : MSE , R-square

驗證模型好壞 : 學習曲線與驗證曲線的比較
