主題 : 房價預測

X = 建物移轉總面積平方公尺 , or plus 屋齡 

y = 總價元

方法 :

  (單特徵)
  
  使用線性迴歸
    
    -Scikit-Learn SGDRegressor(梯度下降)
    
    -Scikit-Learn LinearRegression(正規方程)
  
  
  多項式(Polynomial) 非線性迴歸(from sklearn.preprocessing import PolynomialFeatures)
  
  
  (多特徵)
  
  多變項線性迴歸(加入兩組或兩組以上的特徵來進行預測)
  
    -Scikit-Learn SGDRegressor(梯度下降)
    
    -Scikit-Learn LinearRegression(正規方程)
    

評估標準 : MSE , R-square
